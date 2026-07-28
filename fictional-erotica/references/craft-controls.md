# Craft Controls / 写作控制

Use this reference for scene-level execution. Keep all settings internal unless the user asks to inspect or edit them.

用此参考执行场景层控制。除非用户要求查看或修改，否则所有设置均保留在内部。

## Contents / 目录

- Control priority / 控制优先级
- Core controls / 核心控制
- State and continuity / 状态与连续性
- Response and knowledge / 回应与认知
- Body reality and risk / 身体真实与风险
- Failure, cadence, and aftermath / 失败、段落与事后状态

## Control Priority / 控制优先级

Apply instructions in this order:

依次应用：

1. explicit user instruction / 用户明确要求；
2. established character facts, anatomy, capacity, and hard boundaries / 既定人物事实、身体结构、行动能力与硬边界；
3. relationship history and partner-specific permissions / 关系历史与伴侣特定许可；
4. current scene conditions / 当前场景条件；
5. genre defaults and low-risk inference / 类型默认与低风险推断。

Specific constraints narrow broad presets rather than being averaged away. If equally specific explicit instructions conflict, ask or state the chosen interpretation.

具体限制用于约束宽泛预设，而不是被折中消解。两条同等具体的明确要求冲突时，应询问或说明采用的解释。

## Core Controls / 核心控制

### Explicitness / 页面明确度

| Value | Contract |
|---|---|
| `closed` | desire and consequence on-page; sexual action off-page / 欲望与后果在页面内，性行动在页面外 |
| `sensual` | touch and arousal present; mechanics limited / 呈现触碰与唤起，身体机制有限 |
| `open-door` | acts and bodies clear; sensation and emotion share focus / 行为与身体清楚，感觉与情绪共同成为焦点 |
| `explicit` | concrete anatomy and actions sustained where permitted / 在允许范围内持续呈现具体器官与动作 |

### Scene Focus / 场景重心

- `body-primary`: sexual experience is the main subject / 性经验是主要叙事对象；
- `balanced`: bodily and relational movement share focus / 身体与关系运动共同成为焦点；
- `relationship-primary`: intimacy primarily changes character or relationship / 亲密主要用于改变人物或关系。

Explicitness and focus do not determine activity intensity. Infer intensity from requested acts, tone, established preferences, and current conditions.

页面明确度与场景重心不决定行为强度。强度应由指定行为、基调、既定偏好与当前状态推断。

### Embodied Realism / 具身现实度

`stylized` / 类型化：

- ordinary preparation, cleanup, fatigue, refractory periods, soreness, and recovery may be compressed / 普通准备、清理、疲惫、不应期、酸痛与恢复可以压缩；
- genre-shaped stamina may be idealized / 耐力可以依照类型惯例理想化；
- established anatomy, boundaries, topology, and stated bodily conditions still apply / 既定身体结构、边界、拓扑与明确身体条件仍然有效。

`selective` / 选择性现实，默认：

- include constraints when they affect action, character, pacing, or aftermath / 现实限制影响行动、人物、节奏或事后状态时才进入镜头；
- imply or briefly establish ordinary preparation / 普通准备可以隐含或简短建立；
- foreground one or two relevant frictions, not a complete checklist / 每场突出一两项相关摩擦，而不是完整清单。

`grounded` / 现实向：

- consistently track relevant preparation, protection, fatigue, sensitivity, mess, interruption, cleanup, and recovery / 持续追踪相关准备、保护、疲惫、敏感度、狼藉、中断、清理与恢复；
- let practical limits or failed attempts redirect the scene / 允许现实限制或尝试失败改变场景；
- remain fiction rather than a medical or hygiene manual / 保持文学性，不写成医学或卫生说明书。

### Advanced Internal Profile / 高级内部设置

Infer only what matters:

只推断当前场景需要的内容：

```yaml
advanced_profile:
  camera_distance: external | close | embodied | interior
  action_granularity: compressed | selective | continuous | frame-by-frame
  sensory_weight:
  temporal_profile:
  orgasm_structure:
  mess_visibility: absent | implied | selective | foregrounded
  rhetorical_density: low | intermittent | high
  paragraph_cadence: fragmented | balanced | sustained
```

Do not print or fully populate this profile by default.

默认不要输出，也不要机械填满这份设置。

## State And Continuity / 状态与连续性

Maintain two layers:

维持两个层级：

- **character invariants / 人物不变锚点**: fixed or slow-changing facts such as anatomy, missing features, hair or baldness, scars, disability, aids, preferred terms, and movement limits / 身体结构、缺失特征、头发或秃头、疤痕、残障、辅助器具、偏好称谓与活动限制等固定或缓慢变化的事实；
- **live scene state / 实时场景状态**: posture, orientation, support, clothing, hands, gaze, contact, objects, arousal, fatigue, pain, and mess / 姿势、朝向、支撑、衣物、双手、视线、接触、物件、唤起、疲惫、疼痛与狼藉。

Track only fields that matter:

只追踪相关字段：

```yaml
live_scene_ledger:
  location_and_spatial_anchors:
  participants:
    - posture:
      orientation:
      support_and_balance:
      clothing:
      hands_or_appendages:
      gaze:
      active_contact:
      current_body_state:
  objects_and_props:
  mess_and_cleanup_state:
  elapsed_time_and_recent_transition:
```

Before major transitions, confirm that the new position is reachable, occupied hands or appendages are released or reassigned, and clothing and objects do not silently reset. Distinguish `worn`, `open`, `raised`, `displaced`, `partly removed`, and `removed` when the difference constrains movement.

重大转换前，确认新姿势可以从旧姿势到达，被占用的手或附肢已经释放或重新分配，衣物与物件不会悄悄刷新。差异会限制动作时，应区分穿着、敞开、掀起、拨到一侧、部分脱下与完全脱下。

When a contradiction appears, preserve the most established fact and repair the transition. Do not invent an extra hand, joint, limb, opening, hairstyle, or object to rescue a sentence.

出现矛盾时，保留最牢固的既定事实并修复转换。不要为了挽救一句话而凭空发明额外的手、关节、肢体、开口、发型或物件。

## Response And Knowledge / 回应与认知

Build embodied causality:

建立具身因果：

1. a participant acts / 一位人物行动；
2. affected participants signal, react differently, remain still, or withhold a clear answer / 受影响者给出信号、产生不同反应、保持不动或暂不提供清楚答案；
3. a viewpoint holder observes and interprets, misreads, or remains uncertain / 视角持有者观察并解读、误读或保持不确定；
4. the next action continues, alters, stops, asks, redirects attention, or leaves uncertainty active / 下一步继续、调整、停止、询问、转移注意力或让不确定继续存在。

Distinguish direct sensation, observable signal, inference, established knowledge, and unresolved uncertainty. Bodily response is not automatic proof of desire, consent, emotion, or satisfaction. Do not present convenient mind-reading as fact.

区分直接感觉、可观察信号、推断、既定认知与未解决的不确定。身体反应不自动证明欲望、同意、情绪或满足。不要把方便叙事的读心写成事实。

## Body Reality And Risk / 身体真实与风险

Sexual response settings are tendencies, not guarantees. Duration, erection, lubrication, sensitivity, penetration tolerance, climax, stamina, and recovery vary by occasion, partner, stress, fatigue, medication, pain, and trust. Do not rank bodies by size, endurance, speed, or orgasm count.

性反应设置是倾向，不是保证。持续时间、勃起、润滑、敏感度、承受程度、高潮、耐力与恢复会随场合、伴侣、压力、疲惫、药物、疼痛与信任变化。不得按照尺寸、耐力、速度或高潮次数给身体排序。

For risk-sensitive elements, establish the fictional frame, keep choice and changing capacity legible, write non-instructionally, and track material consequences. Avoid pressure, duration, anatomical, or technique guidance that could function as real-world harm instruction.

处理风险敏感元素时，确立虚构框架，使选择与状态变化清楚可辨，以非指导性方式书写，并追踪物质后果。避免可能构成现实伤害指导的力度、时长、解剖或技术细节。

Choose two or three dominant sensory channels per beat rather than inventorying all five senses. Link detail to action, interpretation, desire, discomfort, adjustment, or memory.

每个节拍选择两到三个主导感官通道，而不是罗列五感。让细节连接行动、解读、欲望、不适、调整或记忆。

## Failure, Cadence, And Aftermath / 失败、段落与事后状态

A scene may remain complete when arousal changes, a position or prop fails, someone laughs or changes their mind, orgasm does not occur, or the original plan is abandoned. Do not automatically convert practical failure into emotional crisis, a desirability thesis, or an inspirational repair speech.

唤起变化、姿势或道具失败、有人笑场或改变主意、没有高潮、原计划被放弃时，场景仍可完整。不要自动把现实失败升级为情感危机、可欲性论文或励志式修复演讲。

Default to balanced paragraphs that complete a coherent action-response-adjustment beat. Use one-sentence paragraphs sparingly for genuine emphasis, interruption, revelation, or abrupt change; do not manufacture urgency by using paragraph breaks as punctuation.

默认使用能够完成动作、回应与调整节拍的均衡段落。单句段仅节制用于真正的强调、中断、揭示或突变；不要把换段当作标点制造紧张感。

Aftermath may include touch, cleanup, space, sleep, conversation, humour, soreness, renewed desire, emotional distance, or departure. In groups, needs may diverge. Do not force identical aftercare or a standard water-and-blanket routine.

事后状态可以包括触碰、清理、空间、睡眠、交谈、幽默、酸痛、重新燃起的欲望、情感距离或离开。多人场景中的需求可以分化。不要强迫统一照料，也不要套用标准饮水加毯子流程。
