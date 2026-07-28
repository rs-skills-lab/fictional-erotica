# Persona And Relationship Input / 人设与关系输入

Use this reference when the user supplies character profiles, wants reusable personae, includes more than two participants, or asks for complex emotional relationships. Accept natural-language description, excerpts, notes, or the structured forms below. The forms are input affordances, not mandatory questionnaires.

当用户提供人物设定、需要可复用人设、包含两人以上参与者或要求复杂情感关系时，使用此参考。接受自然语言描述、节选、笔记或下列结构化形式。这些格式是方便输入的入口，不是必须逐项填写的问卷。

## Contents / 目录

- Input Modes / 输入方式
- Persona Card / 人物卡
- Relationship Graph / 关系图
- Ensemble Scene State / 群像场景状态
- Multi-Partner Craft Rules / 多人写作规则
- Continuity And Revision / 连续性与修订

## Input Modes / 输入方式

Users may provide:

用户可以提供：

- a few decisive traits / 少数具有决定性的特征；
- free-form character and relationship prose / 自由形式的人物与关系描述；
- dialogue, correspondence, scenes, or source excerpts to calibrate voice / 用于校准语言的对白、通信、场景或原文节选；
- one or more structured persona cards / 一张或多张结构化人物卡；
- a relationship graph or an informal description of who wants what from whom / 关系图，或非正式说明谁对谁有何种欲求；
- an existing canon plus requested transformations / 既有原作设定及用户要求的改写。

Extract what is present and infer low-risk gaps. Do not stall drafting to collect every field. Ask only when ambiguity controls adult status, consent, identity, a hard boundary, or the central dramatic premise.

提取已经提供的信息，并推断低风险空缺。不要为了收集所有字段而阻碍起草。只有歧义影响成年身份、同意、人物身份、硬边界或核心戏剧前提时才提问。

Treat the latest explicit instruction as authoritative. Preserve productive contradictions such as `formally controlled / privately hungry` or `loves A / trusts B more`. A persona should constrain choices and voice, not become a list of traits recited in prose.

以用户最新的明确指示为准。保留具有生产力的矛盾，例如 `formally controlled / privately hungry（表面克制 / 私下饥渴）` 或 `loves A / trusts B more（爱 A / 却更信任 B）`。人设应约束人物的选择与语言，而不是变成正文里逐项背诵的性格清单。

## Persona Card / 人物卡

Users may use any subset:

用户可以只填写其中任意部分：

```yaml
persona:
  name:
  pronouns:
  adult_status:
  age_or_life_stage:
  body:
  embodied_constraints:
  public_self:
  private_self:
  voice_fingerprint:
  forbidden_or_uncharacteristic_language:
  desires:
  aversions:
  boundaries:
  touch_and_sex_style:
  preferred_dynamics:
  history:
  vulnerabilities:
  defenses:
  current_emotional_state:
  current_physical_state:
  continuity_anchors:
```

Interpret fields as follows:

各字段解释如下：

- **body / 身体**: concrete embodiment without ranking desirability / 具体描写身体，但不对可欲性作等级评判；
- **embodied constraints / 身体约束**: disability, pain, fatigue, medication, dysphoria, accessibility, recovery, contraception, or other material facts / 残障、疼痛、疲惫、药物、性别烦躁、无障碍需求、恢复状态、避孕或其他物质事实；
- **public/private self / 公开与私下的自我**: what changes with audience, safety, intimacy, status, or shame / 随观众、安全感、亲密程度、身份地位或羞耻而变化的部分；
- **voice fingerprint / 语言指纹**: vocabulary, syntax, formality, humor, profanity, pet names, pauses, and speech under intensity / 词汇、句法、正式程度、幽默、脏话、昵称、停顿，以及高强度状态下的语言；
- **forbidden language / 禁用语言**: words, tones, declarations, or archetypal behavior that would break character / 会导致人物出戏的词语、语气、宣言或类型化行为；
- **desires/aversions/boundaries / 欲望、厌恶与边界**: related but not interchangeable; dislike is not automatically a hard limit / 三者相关但不可互换；不喜欢不自动等于硬边界；
- **touch and sex style / 触碰与性爱风格**: how this person initiates, responds, attends, asks, yields, directs, or reconnects after a misread, crossed line, or emotional shift / 此人如何发起、回应、关注、请求、顺从或让出主动权、引导，以及如何在误读、越界或情绪波动后重新建立连接；
- **history/vulnerability/defenses / 历史、脆弱与防御**: causes of present choices, not diagnoses to explain on the page / 它们是当下选择的成因，而不是必须在正文中解释的诊断；
- **current state / 当前状态**: scene-local conditions that may override usual behavior / 可能暂时覆盖惯常行为的场景局部状态；
- **continuity anchors / 连续性锚点**: promises, habits, private language, prior acts, unresolved conflicts, and recurring motifs / 承诺、习惯、私人语言、既往行为、未解决冲突与反复母题。

When several cards are supplied, do not normalize their detail levels or voices. One highly specified character and one lightly sketched character may coexist; invent only enough for the latter to remain a subject.

收到多张人物卡时，不要强行统一其细节密度或语言。一个高度具体的人物与一个仅有轮廓的人物可以共存；为后者补充的信息只需足以使其仍然是能作出选择、改变场景的完整人物。

## Relationship Graph / 关系图

Represent an ensemble as nodes plus relevant directed or pairwise edges. A group label such as `triad`, `open marriage`, or `polycule` is useful but insufficient. A `metamour` is a partner's other partner, not automatically one's own lover.

把群像表示为人物节点以及相关的有向或双向关系边。`triad（三人关系）`、`open marriage（开放婚姻）` 或 `polycule（多元亲密关系网络）` 等群体标签有用，但并不足够。`metamour（伴侣的另一位伴侣）` 并不自动意味着此人也是自己的恋人。

```yaml
relationship:
  participants: [A, B, C]
  group_form:
  public_status:
  shared_history:
  current_group_tension:
  edges:
    - pair: [A, B]
      label:
      attraction:
      love:
      trust:
      sexual_history:
      power_and_dependency:
      jealousy_compersion_rivalry:
      shared_secrets:
      unequal_knowledge:
      negotiated_boundaries:
      immediate_wants:
      feared_outcome:
```

Record direction when feelings differ:

感情不对称时记录方向：

```yaml
attraction:
  A_to_B:
  B_to_A:
```

Useful edge variables include:

有用的关系边变量包括：

- relationship label and whether both people use the same label / 关系标签，以及两人是否使用同一个标签；
- attraction, romantic love, attachment, loyalty, and trust as separate axes / 把吸引、浪漫爱情、依恋、忠诚与信任视为不同轴线；
- sexual familiarity and what remains new / 性熟悉程度，以及哪些内容仍属新鲜；
- authority, dependency, status, caregiving, or practical leverage / 权威、依赖、地位、照护或现实筹码；
- jealousy, compersion, rivalry, protectiveness, resentment, and curiosity / 嫉妒、共悦、竞争、保护欲、怨恨与好奇；
- shared secrets and unequal knowledge / 共同秘密与不对称信息；
- negotiated permissions, hard limits, and unresolved assumptions / 已协商许可、硬边界与尚未解决的默认假设；
- what each person wants from the other and from the wider group / 每个人想从对方及更大群体中得到什么；
- what would make this edge strengthen, fracture, or change name / 什么会使这条关系边增强、断裂或改变名称。

Do not infer that:

不要推断：

- everyone desires everyone / 所有人都欲望所有人；
- love or consent is symmetrical / 爱或同意天然对称；
- a couple is automatically the emotional center / 某对伴侣自动成为情感中心；
- a third participant exists to improve or test the couple / 第三人存在的意义是改善或考验核心伴侣；
- jealousy means failure, or compersion means the absence of pain / 嫉妒意味着失败，或共悦意味着没有痛苦；
- equality requires identical acts, time, or emotional roles / 平等要求完全相同的行为、时间或情感角色。

## Ensemble Scene State / 群像场景状态

Before drafting, choose:

起草前选择：

- **POV holder / 视角持有者**: whose perceptions organize the prose / 谁的感知组织全文；
- **focal edge / 焦点关系边**: the relationship most changed by this scene / 在本场景中变化最大的关系；
- **group turn / 群体转折**: what changes for the ensemble as a whole / 群体整体发生了什么变化；
- **attention pattern / 注意力模式**: concentrated, alternating, circulating, staged, competitive, collaborative, or deliberately uneven / 集中、交替、循环、分阶段、竞争、协作或有意不均；
- **entry state / 入场状态**: who begins together, arrives later, watches first, or initiates / 谁一开始就在一起、谁稍后到来、谁先观看、谁发起；
- **physical topology / 身体拓扑**: positions, orientation, reach, lines of sight, occupied hands, clothing, and objects / 位置、朝向、可触及范围、视线、双手状态、衣物与物件；
- **knowledge map / 信息地图**: who knows each desire, rule, secret, or prior event / 谁知道每一项欲望、规则、秘密或既往事件；
- **exit state / 离场状态**: who remains close, separates, sleeps, talks, leaves, or understands the relationship differently / 谁继续靠近、分开、睡下、交谈、离开，或以不同方式理解这段关系。

Use a compact private ledger when the scene is long:

场景较长时，使用简洁的内部状态表：

| Person / 人物 | Immediate want / 即时欲望 | Current contact / 当前接触 | Attention given/to whom / 注意力给予谁 | Arousal/comfort / 唤起与舒适度 | Emotional change / 情感变化 |
|---|---|---|---|---|---|
| A |  |  |  |  |  |
| B |  |  |  |  |  |
| C |  |  |  |  |  |

Also track live edges separately. A group-level mood cannot substitute for pairwise responses.

同时分别追踪正在起作用的关系边。群体层面的气氛不能替代两人之间的具体回应。

## Multi-Partner Craft Rules / 多人写作规则

- Give every active participant an immediate want, a capacity to respond, and a meaningful state change / 赋予每位活跃参与者一个即时欲望、回应能力和有意义的状态变化。
- Let one action produce different reactions across the group / 让同一个行动在群体中引发不同反应。
- Name or otherwise clarify the actor when pronouns or plural movement become ambiguous / 当代词或复数动作产生歧义时，明确说出行动者或以其他方式澄清。
- Track entry, invitation, waiting, watching, interruption, withdrawal, re-entry, exclusion, and shifting alliances / 追踪进入、邀请、等待、观看、中断、退出、再次加入、排除与变化中的联盟。
- Preserve peripheral subjectivity. A watcher may be central through gaze, instruction, anticipation, jealousy, restraint, or choice without being constantly touched / 保留边缘位置人物作为完整人物的存在；观看者即使没有持续被触碰，也可以通过目光、指令、期待、嫉妒、克制或选择成为中心人物。
- Allocate attention by dramatic purpose, not equal paragraph counts / 按戏剧目的分配注意力，而不是机械地平均段落数量。
- When power differs, distinguish desired erotic power from practical dependency and show how the fiction keeps agency legible / 权力不同时，区分人物想要的情色权力与现实依赖，并让人物的选择权与行动能力清楚可辨。
- Let dirty talk expose different edges: the same line can reassure one person, provoke another, and reveal a secret to a third / 让情色语言显露不同关系边：同一句话可以安抚一个人、挑衅另一个人，并向第三个人泄露秘密。
- Aftermath may diverge. Participants can need different kinds of contact, space, reassurance, humor, cleanup, conversation, or privacy / 事后需求可以分化；参与者可以需要不同程度或类型的接触、空间、安抚、幽默、清理、交谈或隐私。

## Continuity And Revision / 连续性与修订

For recurring personae, retain:

对于反复出现的人设，保留：

- stable voice fingerprints and forbidden expressions / 稳定的语言指纹与禁用表达；
- embodied facts and practical constraints / 身体事实与现实约束；
- pairwise histories, permissions, injuries, and private vocabulary / 两两之间的历史、许可、伤痕与私人词汇；
- who knows which facts / 每项事实分别被谁知晓；
- changes caused by prior scenes / 先前场景造成的变化；
- unresolved asymmetries rather than resetting the group to harmony / 尚未解决的不对称，而不是每次都把群体重置成和谐状态。

Before delivery, audit:

交付前检查：

- **identity / 身份**: each person remains recognizable without name labels / 即使遮住姓名，每个人仍然可以被辨认；
- **edge integrity / 关系边完整性**: every important dyad reflects its own history and asymmetry / 每一组重要的两人关系都反映其自身历史与不对称；
- **agency / 能动性**: no participant becomes furniture, a reward, or a consent proxy / 没有参与者沦为家具、奖品或替别人表达同意的代理；
- **topology / 拓扑**: bodies, touch, gaze, and movement remain physically possible / 身体、触碰、目光与动作在物理上保持可能；
- **attention / 注意力**: uneven focus is intentional and its emotional effect is legible / 不均衡的焦点来自有意安排，其情感效果清楚可见；
- **change / 变化**: the scene alters at least one person, edge, or group understanding / 场景至少改变一个人物、一条关系边或一种群体理解。
