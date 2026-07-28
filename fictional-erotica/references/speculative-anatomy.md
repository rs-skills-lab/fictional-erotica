# Speculative Anatomy / 幻想身体结构

Load this module only when the user explicitly requests or establishes nonhuman, tentacular, alien, demonic, vampiric, shapeshifting, mechanical, magical, or otherwise nonstandard fictional bodies.

只有用户明确要求或已经设定人外、触手、外星、恶魔、吸血鬼、变形、机械、魔法或其他非标准虚构身体时，才加载此模块。

```yaml
speculative_anatomy:
  enabled: false
```

## Embodied Coherence / 具身一致性

Nonhuman form does not remove established anatomy, capacity, physical topology, communication patterns, or character identity. Treat unusual morphology as a body plan to be tracked, not a licence for spatial or causal incoherence.

非人形态不取消既定身体结构、行动能力、物理拓扑、交流方式或人物身份。应把异常形态作为需要追踪的身体图谱，而不是取消空间与因果一致性的许可。

## Body Plan / 身体图谱

Establish only relevant fields:

只建立相关字段：

```yaml
speculative_anatomy:
  enabled: true
  species_or_form:
  body_plan:
    humanoid_core:
    additional_appendages:
      type:
      count:
      independent_control:
      dexterity:
  sensory_map:
  physical_properties:
    texture:
    temperature:
    strength:
    flexibility:
  compatibility:
    size_adjustment:
    shape_adjustment:
    regeneration:
  communication:
    speech:
    telepathy:
    tactile_signals:
  reproductive_logic:
  fluid_properties:
  preferred_terms:
```

Do not infer personality, dominance, cruelty, sexual role, or relationship meaning from species or morphology alone.

不得仅由种族或形态推断人物性格、支配性、残酷程度、性角色或关系意义。

## Appendage Ledger / 附肢账本

For multiple independently controlled appendages, assign stable identifiers and update them across beats:

存在多条可独立控制的附肢时，为其分配稳定编号，并随节拍更新：

```yaml
appendage_ledger:
  a1: supporting_back
  a2: holding_left_wrist
  a3: sensory_contact
  a4: inactive
  a5: stabilizing_body
  a6: interacting_with_environment
```

One appendage cannot simultaneously perform incompatible actions. Do not let counts multiply or disappear without an established transformation.

同一附肢不能同时执行不相容动作。除非已经建立变形规则，不要让数量凭空增加或消失。

Additional limbs should have differentiated functions such as support, wrapping, sensory exploration, balance, restraint, communication, temperature, vibration, or environmental interaction. Do not treat every appendage as a duplicate penetrative organ.

额外肢体应承担不同功能，例如支撑、包裹、感官探索、平衡、限制、交流、温度、振动或与环境互动。不要把每条附肢都写成重复的插入器官。

## Speculative Physics / 幻想物理

```yaml
speculative_physics:
  level: grounded | coherent | dreamlike | maximalist
```

- `grounded`: unusual anatomy follows strict established physiology and physics / 异常身体严格遵循已建立的生理与物理规则；
- `coherent`: default; fantasy anatomy is possible but remains internally consistent / 默认；允许幻想身体，但保持内部一致；
- `dreamlike`: transformation, space, or count may be symbolic while the scene remains intelligible / 变形、空间或数量可以带象征性，但场景仍可理解；
- `maximalist`: highly type-driven adaptation, regeneration, scale, or sensation may occur under explicit world rules / 在明确世界规则下，允许高度类型化的适配、再生、尺度或感官。

Even dreamlike scenes need stable viewpoint, agency, and locally intelligible action.

即使梦境化场景，也需要稳定视角、能动性与局部可理解的行动。

## Reproductive And Consequence Logic / 生殖与后果逻辑

Do not automatically apply human pregnancy, ejaculation, cycles, infection, recovery, or anatomy to a nonhuman body. Establish fictional rules only when relevant, and keep them consistent with the chosen embodied realism.

不要自动把人类怀孕、射精、周期、感染、恢复或身体结构套到非人身体上。只有相关时才建立虚构规则，并与所选具身现实度保持一致。
