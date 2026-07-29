# Sexual Roles / 攻受与行为角色

Use this module when the user specifies or asks to configure top/bottom, gong/shou, giver/receiver, insertive/receptive, switching, fluid, scene-specific, or other relationship-specific sexual roles. This module applies to original characters and fanfiction alike.

用户指定或要求配置 top/bottom、攻受、给予/接受、插入/接受、可逆、流动、本场例外或其他关系特定的性角色时，使用本模块。本模块同时适用于原创人物与同人角色。

## Contents / 目录

- Shared role configuration / 通用角色配置
- Pairwise roles in groups / 多人场景中的两两角色
- Role, power, identity, and anatomy / 角色、权力、身份与身体
- Scene execution and continuity / 场景执行与连续性
- Console and audit / 控制台与审计

## Shared Role Configuration / 通用角色配置

Treat explicit role assignments as important relationship and scene facts:

把用户明确指定的攻受与行为角色视为重要的关系及场景事实：

```yaml
sexual_role_configuration:
  terminology: top-bottom | gong-shou | giver-receiver | insertive-receptive | custom
  scope: relationship | participant | current-scene
  assignments:
    A:
    B:
  pattern: fixed | switching | fluid | scene-specific
  current_scene:
  exceptions:
```

For a dyad, participant assignments may be sufficient. For more than two participants, or when the same person has different roles with different partners, use pairwise assignments instead of one global role label.

两人关系中，逐人 assignments 通常已经足够。参与者超过两人，或同一人物面对不同伴侣拥有不同角色时，应使用两两配置，而不是一套全局标签。

```yaml
pairwise_sexual_roles:
  A-B:
    sexual_relationship: true
    terminology: top-bottom
    pattern: fixed
    assignments:
      A: top
      B: bottom
    current_scene:
    exceptions:

  B-C:
    sexual_relationship: true
    terminology: gong-shou
    pattern: switching
    assignments:
      B:
      C:
    current_scene:

  A-C:
    sexual_relationship: false
    sexual_touch: prohibited
```

An explicit assignment overrides generic inference. Preserve fixed roles when requested; support switching, fluid, or scene-specific roles when requested. A current-scene exception does not silently rewrite the established relationship pattern.

用户明确指定时，优先于模型的通用推断。要求固定角色时保持固定；要求可逆、流动或本场例外时按设定执行。本场例外不得静默改写既定关系模式。

## Pairwise Roles In Groups / 多人场景中的两两角色

Do not create one global hierarchy for a group unless the user explicitly requests it. Track role, permission, attraction, and physical reach by relationship edge.

除非用户明确要求，不要为多人关系建立一套全局等级。按关系边分别追踪角色、许可、吸引与身体可达性。

A role on one edge does not transfer to another:

一条关系边上的角色不会自动转移到另一条关系边：

```text
A tops B
≠ A tops everyone
≠ A may touch C
≠ B has the same role with C
```

Agreement, permission, and role vocabulary do not transfer across participants. In group scenes, name actors when pronouns or omitted subjects obscure agency, topology, or which relationship edge is active.

同意、许可与角色词汇不能跨人传递。多人场景中，代词或省略主语使能动性、身体拓扑或当前关系边含混时，应明确点名行动者。

## Role, Power, Identity, And Anatomy / 角色、权力、身份与身体

Do not infer any of the following from one another unless the user or established character facts explicitly connect them:

除非用户或既定人物事实明确建立联系，不得让以下项目彼此自动推导：

- top or bottom / top 或 bottom；
- gong or shou / 攻或受；
- giver or receiver / 给予或接受；
- insertive or receptive action / 插入或接受行为；
- dominance or submission / 支配或臣服；
- social power / 社会权力；
- temperament / 性格；
- masculinity or femininity / 阳刚或阴柔；
- emotional dependence / 情感依赖；
- gender identity or presentation / 性别身份或呈现；
- anatomy / 身体结构；
- sexual orientation / 性取向。

A character may be socially powerful and sexually receptive, emotionally dependent and sexually insertive, fixed in one role with one partner and switching with another, or use role terms without any dominance hierarchy.

人物可以拥有较高社会权力却在行为中接受，可以情感依赖却承担插入角色，可以与一个伴侣固定、与另一个伴侣可逆，也可以使用攻受词汇而不存在支配等级。

## Scene Execution And Continuity / 场景执行与连续性

Role configuration should affect only consequences that matter to the requested scene, such as:

角色配置只应在与当前场景有关时产生后果，例如：

- anticipation and learned expectations / 期待与习得预期；
- reachable physical action and position / 可实现的身体动作与姿势；
- preparation or bodily constraints / 准备与身体限制；
- partner-specific vocabulary / 伴侣特定词汇；
- initiation, guidance, or redirection habits / 发起、引导与改道习惯；
- relationship tension or deliberate role reversal / 关系张力或有意角色反转；
- cross-scene continuity / 跨场景连续性。

Do not flatten a character into a role label. Ordinary speech, attention, hesitation, humour, affection, conflict, and changing body state remain character-specific.

不要把人物压扁成角色标签。普通语言、注意方式、犹豫、幽默、依恋、冲突与身体状态变化仍应属于具体人物。

Track established role patterns in the relationship or cross-scene ledger. Do not rediscover a fixed or familiar role as new in every scene. Preserve requested exceptions without turning them into permanent changes unless the user establishes that change.

在关系或跨场景账本中追踪既定角色模式。不要每场重新发现已经固定或熟悉的角色。本场例外应被保留，但除非用户明确建立变化，不得自动变成永久改写。

## Transformations And Canon / 改写与原作

Gender transformation, anatomy change, species change, AU role mapping, social-status swap, or other transformations do not automatically change sexual-role configuration. Use [canon-grounding-and-fanfiction.md](canon-grounding-and-fanfiction.md) when canon or AU continuity is relevant, but keep the shared role schema here as the single source of truth.

性转、身体改写、种族变化、AU 身份映射、社会地位互换或其他改写都不会自动改变攻受配置。涉及原作或 AU 连续性时，使用 [canon-grounding-and-fanfiction.md](canon-grounding-and-fanfiction.md)，但以本文件作为通用角色 schema 的唯一正式定义。

An explicit transformation may change a role only when the user states that change, or when an unavoidable physical consequence creates a genuine conflict that requires one concise clarification.

只有用户明确指定角色变化，或身体改写产生无法回避的真实冲突并需要一次简短澄清时，transformation 才能改变角色配置。

## Console / 控制台

When the advanced console is requested and sexual roles materially matter, surface only the relevant fields:

用户要求高级控制台且攻受或行为角色会实质影响场景时，只展示相关字段：

```yaml
sexual_role_configuration:
  terminology:
  scope:
  pattern:
  assignments_or_pairwise_edges:
  current_scene:
  exceptions:
  global_hierarchy: none | user-specified
```

Do not force users to configure sexual roles when they have not requested them and the scene does not require the distinction.

用户没有指定，且场景不需要区分时，不得强迫用户配置攻受或行为角色。

## Audit / 审计

Before delivery, silently check:

交付前静默检查：

- explicit assignments override stereotype-based inference / 明确指定优先于刻板推断；
- fixed, switching, fluid, and scene-specific patterns remain distinct / 固定、可逆、流动与本场例外保持区分；
- pairwise roles do not become a global group hierarchy / 两两角色没有变成全局多人等级；
- roles, permissions, and vocabulary do not transfer across relationship edges / 角色、许可与词汇没有跨关系边传递；
- current-scene exceptions do not silently rewrite established patterns / 本场例外没有静默改写既定模式；
- power, personality, gender, anatomy, orientation, dependence, and role are not collapsed / 权力、性格、性别、身体、取向、依赖与角色没有混为一谈；
- role configuration changes physical possibility and anticipation without replacing the character / 角色配置影响身体可能性与期待，但没有替换人物；
- transformations do not silently reassign roles / 改写没有静默重新分配角色；
- role controls and ledger terminology do not leak into scene prose / 角色控制项与账本术语没有泄露进正文。
