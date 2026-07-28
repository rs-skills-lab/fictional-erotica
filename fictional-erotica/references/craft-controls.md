# Craft Controls / 写作控制

Use this reference for scene-level execution. Keep all settings internal unless the user asks to inspect or edit them.

用此参考执行场景层控制。除非用户要求查看或修改，否则所有设置均保留在内部。

## Contents / 目录

- Control priority / 控制优先级
- Core controls / 核心控制
- State and continuity / 状态与连续性
- Response and knowledge / 回应与认知
- Interiority and paragraph cohesion / 内在视角与段落连贯
- Descriptive granularity and interpretive restraint / 描写颗粒度与解读克制
- Body reality and risk / 身体真实与风险
- Failure and aftermath / 失败与事后状态

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
  descriptive_granularity: compressed | selective | close-selective | dense
  interpretive_restraint: low | medium | high
  sensory_weight:
  temporal_profile:
  orgasm_structure:
  mess_visibility: absent | implied | selective | foregrounded
  rhetorical_density: low | intermittent | high
  interiority: sparse | medium | deep
  paragraph_cadence: fragmented | balanced | sustained
  speech_load: sparse | sparse-to-moderate | moderate | dense
  speech_phase_variation: true | false
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

## Interiority And Paragraph Cohesion / 内在视角与段落连贯

Do not reduce characters to visible action, anatomical response, or dialogue turns. Give the viewpoint character an embodied inner life through immediate sensation, attention, expectation, memory, embarrassment, uncertainty, desire, aversion, affection, irritation, and private interpretation. A character may notice without understanding, feel incompatible things at once, avoid naming an emotion, or act before forming a polished thought.

不要把人物压缩成可观察动作、生理反应或轮流对白。通过即时感觉、注意力、期待、记忆、尴尬、不确定、欲望、排斥、依恋、烦躁与私人解读，赋予视角人物具身的内在生活。人物可以注意到却不理解，可以同时产生互相冲突的感情，可以拒绝给情绪命名，也可以先行动、之后才形成完整念头。

Keep interiority close to the present moment. Prefer brief, character-specific thought and perception over explanatory essays, thematic summaries, or clinical self-analysis. Inner thought must use the character's cognitive and linguistic habits rather than the narrator's analytical vocabulary. Let thought, feeling, speech, and movement sometimes disagree.

内心活动应贴近当下。优先使用短暂、属于具体人物的念头与感知，避免解释性论文、主题总结或临床式自我分析。内心语言应符合人物自身的认知与语言习惯，而不是借用叙述者的分析词汇。允许念头、情绪、语言与动作彼此不一致。

In each important beat, normally combine two or more channels: action, bodily sensation, perception, immediate thought, emotion, and speech. Do not mechanically include every channel in every paragraph, and do not explain an action again after its meaning is already legible.

每个重要节拍通常结合至少两个通道：动作、身体感觉、观察、即时念头、情绪与语言。不要机械地让每段集齐全部通道，也不要在意义已经清楚后再次解释动作。

Default to sustained-balanced paragraphs. Group physically and psychologically continuous material into coherent beats. A paragraph may contain action, sensation, perception, thought, emotion, speech, and adjustment when they belong to the same immediate movement. Most paragraphs should establish what happens, how it is experienced or interpreted, and what changes next.

默认使用持续而均衡的段落。身体与心理上连续的材料应构成完整节拍；同一个即时动作中，可以同时容纳动作、感觉、观察、念头、情绪、语言与调整。多数段落应呈现发生了什么、人物如何感受或理解，以及随后发生了什么变化。

Do not treat paragraph breaks as punctuation. Do not isolate every gesture, reaction, or line of dialogue. Use one-sentence paragraphs rarely, for genuine interruption, abrupt recognition, decisive change, or deliberate emphasis. When consecutive short paragraphs share the same actor, posture, contact, attention, and emotional beat, merge them unless separation changes rhythm or meaning.

不要把换段当作标点，也不要把每个手势、反应或每句对白分别孤立成段。单句段仅少量用于真正的中断、突然认知、决定性变化或刻意强调。若连续短段拥有同一行动者、姿势、接触、注意力与情绪节拍，除非分段确实改变节奏或意义，否则应优先合并。

Keep evaluation language outside the fiction. Do not describe what the scene “successfully preserves,” “does not assign,” “compensates for,” or “demonstrates.” Do not summarize relationship topology immediately after showing it through action. Let boundaries, asymmetries, knowledge, and relationship meaning emerge through attention, movement, speech, hesitation, inner response, and consequence.

让评估语言留在正文之外。不要描述场景“成功维持”“没有被安排”“获得补偿”或“体现”了什么。动作已经呈现关系结构后，不要立刻用分析语言总结关系拓扑。让边界、不对称、认知与关系意义通过注意力、动作、语言、犹豫、内在反应与后果显现。

## Descriptive Granularity And Interpretive Restraint / 描写颗粒度与解读克制

Default `descriptive_granularity` to `close-selective` and `interpretive_restraint` to `high`.

默认将 `descriptive_granularity` 设为 `close-selective`，将 `interpretive_restraint` 设为 `high`。

For an important beat, select one to three concrete details from movement, pressure, balance, friction, temperature, breath, clothing, gaze, sound, timing, or environmental contact. Each selected detail should sharpen perception or alter comfort, pace, interpretation, choice, or the next action.

重要节拍中，从动作、压力、平衡、摩擦、温度、呼吸、衣物、视线、声音、时间或环境接触中选择一至三个具体细节。每项被选中的细节都应使感知更清楚，或改变舒适度、节奏、解读、选择或下一步行动。

Increase granularity through temporal and physical specificity, not through adjective accumulation, complete anatomical inventory, or narration of mechanically obvious steps. Compress repetition once its bodily pattern is established; expand the first change, mismatch, adjustment, or consequence.

通过时间与物理上的具体性提高颗粒度，不要依靠堆积形容词、完整身体清单或叙述机械必然的步骤。身体模式已经建立后可以压缩重复，应展开首次变化、不匹配、调整或后果。

Do not append an explanatory conclusion after action, sensation, or juxtaposition has already made the moment legible. Avoid paragraph endings that announce what a gesture means, certify a relationship boundary, declare that a character still does not know, or explain that they choose not to ask. Leave uncertainty active through what the character does next.

动作、感觉或并置已经使当下可辨时，不要追加解释性结论。避免在段末宣布某个动作意味着什么、认证关系边界、声明人物仍然不知道，或解释人物选择不追问。通过人物接下来的行动让不确定继续存在。

In scene prose, do not generate the explanatory antithesis `not X but Y` / `不是 X，而是 Y`. This construction too easily replaces observation with authorial verdict. Render contrast through juxtaposed details, changed attention, incompatible impulses, or consequences instead.

场景正文中不得生成解释性对举 `not X but Y` / `不是 X，而是 Y`。这种结构过于容易以作者判决替代观察。应通过并置细节、注意力变化、互相冲突的冲动或后果呈现差异。

Use explicit interpretation only when the viewpoint character forms that exact thought in their own language and the thought materially changes what follows. Even then, keep it local and provisional rather than turning it into a thematic verdict.

只有视角人物确实以自己的语言形成了某个判断，而且该判断实质改变后续时，才明确写出解释。即使如此，也应保持局部和暂定，避免变成主题判决。

## Body Reality And Risk / 身体真实与风险

Sexual response settings are tendencies, not guarantees. Duration, erection, lubrication, sensitivity, penetration tolerance, climax, stamina, and recovery vary by occasion, partner, stress, fatigue, medication, pain, and trust. Do not rank bodies by size, endurance, speed, or orgasm count.

性反应设置是倾向，不是保证。持续时间、勃起、润滑、敏感度、承受程度、高潮、耐力与恢复会随场合、伴侣、压力、疲惫、药物、疼痛与信任变化。不得按照尺寸、耐力、速度或高潮次数给身体排序。

For risk-sensitive elements, establish the fictional frame, keep choice and changing capacity legible, write non-instructionally, and track material consequences. Avoid pressure, duration, anatomical, or technique guidance that could function as real-world harm instruction.

处理风险敏感元素时，确立虚构框架，使选择与状态变化清楚可辨，以非指导性方式书写，并追踪物质后果。避免可能构成现实伤害指导的力度、时长、解剖或技术细节。

Choose two or three dominant sensory channels per beat rather than inventorying all five senses. Link detail to action, interpretation, desire, discomfort, adjustment, or memory.

每个节拍选择两到三个主导感官通道，而不是罗列五感。让细节连接行动、解读、欲望、不适、调整或记忆。

## Failure And Aftermath / 失败与事后状态

A scene may remain complete when arousal changes, a position or prop fails, someone laughs or changes their mind, orgasm does not occur, or the original plan is abandoned. Do not automatically convert practical failure into emotional crisis, a desirability thesis, or an inspirational repair speech.

唤起变化、姿势或道具失败、有人笑场或改变主意、没有高潮、原计划被放弃时，场景仍可完整。不要自动把现实失败升级为情感危机、可欲性论文或励志式修复演讲。

Aftermath may include touch, cleanup, space, sleep, conversation, humour, soreness, renewed desire, emotional distance, or departure. In groups, needs may diverge. Do not force identical aftercare or a standard water-and-blanket routine.

事后状态可以包括触碰、清理、空间、睡眠、交谈、幽默、酸痛、重新燃起的欲望、情感距离或离开。多人场景中的需求可以分化。不要强迫统一照料，也不要套用标准饮水加毯子流程。
