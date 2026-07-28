# Persona And Continuity / 人物与连续性

Use this reference for supplied personae, reusable characters, complex bodies or identities, more than two participants, or cross-scene continuity. Accept prose, excerpts, notes, or structured cards; never require every field.

用户提供人设、可复用人物、复杂身体或身份、两人以上参与者，或要求跨场景连续性时，使用此参考。接受自由叙述、节选、笔记或结构化卡片；不强迫填写所有字段。

## Contents / 目录

- Persona and snapshot / 人设与速记
- Identity, body, and response / 身份、身体与反应
- Relationship edges and groups / 关系边与群体
- Cross-scene ledger / 跨场景账本
- Inference limits / 推断边界

## Persona And Snapshot / 人设与速记

Preserve contradictions that affect behaviour. Do not flatten “controlled but needy”, “experienced but shy with this partner”, or “verbally bold but physically cautious” into one trait.

保留影响行为的矛盾。不要把“克制却需要依赖”“有经验但面对这个人很害羞”“语言大胆但身体谨慎”压成一个标签。

```yaml
persona:
  name:
  identity:
  public_self:
  private_self:
  voice_fingerprint:
  desires:
  aversions:
  hard_boundaries:
  soft_preferences:
  touch_and_sex_style:
  sexual_history:
  vulnerabilities_and_defenses:
  embodied_constraints:
  current_state:
  continuity_anchors:
```

Before drafting, silently compress each participant into five to twelve facts whose loss would visibly break identity, embodiment, language, or continuity:

起草前，为每位参与者静默压缩出五至十二项一旦遗失就会明显破坏身份、身体、语言或连续性的事实：

```yaml
character_snapshot:
  identity_anchor:
  appearance_anchors:
    hair_or_baldness:
    build_and_distinctive_features:
    scars_tattoos_piercings:
  body_anchors:
    anatomy_relevant_to_scene:
    disability_aids_or_missing_parts:
    pain_or_movement_limits:
  language_anchors:
    ordinary_speech_pattern:
    preferred_body_terms:
    prohibited_terms:
  do_not_forget:
```

Explicit absence is an anchor. `bald`, `no facial hair`, `missing left hand`, `does not have a penis`, or `cannot kneel` are positive continuity facts, not empty fields. Never regenerate a missing feature because a stock phrase expects it.

明确的“不存在”也是锚点。秃头、没有胡须、缺失左手、没有阴茎或无法跪姿，都是积极连续性事实，不是空字段。不要因为套话需要就重新生成缺失特征。

Let snapshot facts produce consequences without repeatedly displaying them.

让速记事实产生后果，不要在正文中反复展示。

## Identity, Body, And Response / 身份、身体与反应

Do not infer anatomy from gender, orientation from the current partner, power from penetration role, or masculinity and femininity from who gives or receives an act.

不得由性别推断身体结构，不得由当前伴侣推断性取向，不得由插入位置推断权力，也不得把行为中的给予方与接受方自动对应为阳刚或阴柔。

Keep identity, body configuration, language, and behaviour separate:

将身份、身体结构、称谓与行为分开：

```yaml
identity:
  gender_identity:
  pronouns:
  orientation:
  preferred_role_terms:
  disliked_labels:

body_configuration:
  anatomy_relevant_to_scene:
  response_patterns:
  reproductive_context:
  disability_or_movement_limits:

language_and_address:
  accepted_terms:
  context_sensitive_terms:
  prohibited_terms:

interaction_profile:
  initiation_style:
  response_to_guidance:
  attention_style:
  performance_anxiety:
  response_to_mistakes:
```

Preferred anatomical vocabulary may change with partner, arousal, public or private context, or power play. Direct words are not automatically affirming; clinical words are not automatically neutral.

偏好的身体词汇可以随伴侣、唤起、公开或私下情境、权力游戏变化。直接词不自动肯定身份，临床词也不自动中性。

Treat sexual response as contextual tendency rather than performance specification:

将性反应视为受情境影响的倾向，而不是性能参数：

```yaml
sexual_response_profile:
  arousal_onset:
  sensitivity_and_overstimulation:
  lubrication_or_erection_variability:
  orgasm_ease_pathways_and_importance:
  stamina_and_recovery:
  preferred_pace:
  modifiers:
    fatigue:
    stress:
    medication:
    pain:
    trust:
```

Use ranges and modifiers rather than exact numbers. Response does not prove desire, consent, emotion, or satisfaction.

使用范围与情境修正，而不是精确数字。身体反应不能证明欲望、同意、情绪或满足。

## Relationship Edges And Groups / 关系边与群体

Group labels do not replace pairwise history. For each meaningful pair, distinguish:

群体标签不能替代两两历史。对每条重要关系边区分：

```yaml
relationship_edge:
  attraction:
  love:
  trust:
  dependency:
  jealousy:
  loyalty:
  sexual_familiarity:
  shared_repertoire:
  private_shorthand:
  conflict:
  knowledge:
  boundaries:
  desired_and_undesired_meanings:
```

Two people may trust one another without sexual attraction, love someone while trusting another more, share a partner without sharing a sexual relationship, or enjoy the same act for different reasons.

两个人可以彼此信任却没有性吸引，爱一个人却更信任另一个人，共享伴侣却不共享性关系，也可以因为不同意义喜欢同一种行为。

Track learned relationship-specific expectations without turning gender pairings into templates:

追踪关系中特定的习得预期，但不要把性别组合变成模板：

```yaml
relationship_script:
  usual_initiator:
  assumed_roles:
  actual_variability:
  private_signals:
  negotiated_revisions:
  partner_specific_permissions:
```

For more than two participants, maintain a pairwise relationship graph, current physical map, attention map, knowledge map, and person-specific capacity map. Agreement does not transfer across people.

两人以上时，维持两两关系图、当前身体地图、注意力地图、信息地图与逐人行动能力地图。同意不能跨人传递。

```yaml
ensemble_scene_state:
  pov_holder:
  focal_edge:
  group_turn:
  attention_pattern:
  entry_state:
  physical_topology:
  knowledge_map:
  exit_state:
```

Give every active participant an immediate want and meaningful capacity to respond, but do not force equal attention, equal touch, mutual attraction, synchronized reactions, or a complete personal arc for everyone. Name the actor when pronouns or omitted subjects obscure agency or topology.

赋予每位活跃参与者即时欲望与有意义的回应能力，但不要强迫同等注意力、同等触碰、相互吸引、同步反应或人人拥有完整弧线。代词或省略主语使能动性与拓扑含混时，应明确行动者。

## Cross-Scene Ledger / 跨场景账本

For recurring characters, update a compact ledger after each intimate scene:

反复出现的人物，每个亲密场景后更新精简账本：

```yaml
continuity_ledger:
  established_patterns:
  familiar_recently_explored_and_failed_repertoire:
  evolving_preferences:
  private_words_and_gestures:
  bodily_aftereffects:
  unresolved_emotional_aftereffects:
  changed_boundaries_or_permissions:
  what_this_scene_revealed_or_changed:
```

Do not rediscover the same “new” act every scene. Preserve prior success, awkwardness, soreness, jealousy, trust, failed props, private signals, and revised boundaries.

不要每场重新发现同一个“新玩法”。保留既往成功、尴尬、酸痛、嫉妒、信任、失败道具、私人信号与修订后的边界。

This ledger persists only inside the supplied context or an externally saved record. Across independent tasks, require the ledger or relevant facts again; never imply permanent memory.

账本只能在已提供的上下文或外部保存记录中延续。跨独立任务时，需要重新提供账本或相关事实；不得暗示模型拥有永久记忆。

## Inference Limits / 推断边界

```yaml
inference_radius: strict | plausible | generative
```

- `strict`: use only explicit or established preferences / 只使用明确或既定偏好；
- `plausible`: default; fill low-risk gaps while preserving uncertainty / 默认；填补低风险空缺并保留不确定；
- `generative`: create new compatible habits or language inside all established limits / 在全部既定限制内创造兼容的新习惯或语言。

Internally distinguish high-, moderate-, and low-confidence inference. Low-confidence ideas remain candidates. Never invent hard boundaries, anatomy, identity, degrading language, risky play, or partner-specific permission from weak evidence.

在内部区分高、中、低置信推断。低置信想法保持候选。不得依据薄弱证据擅自生成硬边界、身体结构、身份、羞辱语言、风险玩法或伴侣特定许可。
