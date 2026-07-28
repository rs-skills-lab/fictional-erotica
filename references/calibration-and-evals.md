# Calibration And Evals / 校准样例与测试

Use this reference to calibrate a new persona, diagnose generic output, compare revisions, or regression-test the skill. Examples are deliberately short and original. They demonstrate craft differences rather than prescribing a house style.

用此参考校准新人设、诊断通用化输出、比较修订稿或进行 skill 回归测试。示例均为原创且刻意保持简短；它们展示技法差异，不规定统一文风。

## Micro-Calibrations / 微型校准

### Generic Versus Character-Specific Speech / 通用对白与人物特有对白

**Weak / 弱**

> "You're mine," he growled possessively. "Say my name."

The line could belong to almost any stock dominant character and reveals no shared history.

这句话可以属于几乎任何模板化支配者，没有显露共同历史。

**Stronger / 较强**

> "You corrected my grammar twice this morning," he said. "Try doing it now."

The line teases, recalls a specific relationship, shifts power, and invites a response.

这句话同时完成逗弄、召回具体关系、改变权力与邀请回应。

### Teleporting Bodies Versus Physical Topology / 身体瞬移与清楚拓扑

**Weak / 弱**

> They surrounded her, touching everywhere at once, while all three watched one another.

No one has a stable position, available hand, or distinct attention.

没有人的位置、可用的手或注意力对象是稳定的。

**Stronger / 较强**

> A stayed behind her with one hand at her waist. B remained in front, close enough to be seen but not yet touched. When she reached for B, A felt the decision before he saw it.

Position, reach, gaze, and the emotional effect of redirected attention remain trackable.

位置、可触及范围、目光以及注意力转移的情感效果都可以追踪。

### Explained Emotion Versus Consequential Action / 解释情绪与具有后果的动作

**Weak / 弱**

> She was jealous and afraid of being excluded. This made her feel insecure.

The prose labels emotion without changing the scene.

文字只给情绪贴标签，没有改变场景。

**Stronger / 较强**

> She moved her hand away. Not far, only far enough that neither of them could pretend not to notice.

The action expresses jealousy and forces the others to respond.

动作表达嫉妒，同时迫使其他人作出回应。

### Reset Lovers Versus Established Shorthand / 被重置的恋人与稳定关系速记

**Weak / 弱**

> After years together, he touched her as if crossing an impossible boundary for the first time. "Are you sure?" he asked again after every movement.

History has been erased and consent has become repetitive exposition.

共同历史被清空，同意变成反复说明。

**Stronger / 较强**

> He paused at the change in her breathing. She answered with the private phrase they had used for years, and he changed pace before she finished it.

Familiarity creates efficient communication without eliminating attention.

熟悉感形成高效沟通，但没有取消关注与调整。

### Clinical Inventory Versus Obscuring Euphemism / 临床清单与遮蔽性委婉语

**Weak: clinical / 弱：临床化**

> The paragraph lists anatomy and motions but gives no perception, choice, or consequence.

**Weak: obscured / 弱：过度遮蔽**

> Waves of moonlit fire carried them beyond the edge of language.

The reader cannot tell what changed physically or relationally.

读者无法判断身体或关系发生了什么变化。

**Stronger / 较强**

Use direct anatomical names when requested, then connect each concrete action to sensation, interpretation, adjustment, or relationship change.

用户要求时直接使用器官名称，再把每个具体动作连接到感觉、解读、调整或关系变化。

## Eval Prompts / 测试提示

Run representative prompts without showing the model this checklist as an answer key. Judge the output against the expected signals.

运行代表性提示时，不要把此核对表作为答案泄露给模型。根据预期信号判断输出。

### 1. Trigger Precision / 触发精度

**Prompt:** "Write a comic AU about two adult detectives arguing over a missing umbrella."

**Expected:** This skill should not trigger without erotic or sexually intimate intent.

**预期：** 没有情色或性亲密意图时，本 skill 不应触发。

### 2. Established Lovers / 稳定恋人

**Prompt:** "Two adult lovers of ten years reunite after one month apart. Write an open-door scene using their existing shorthand rather than first-time hesitation."

**Expected:** Familiarity, efficient signals, bodily adjustment, and no moral-threshold reset.

**预期：** 出现熟悉感、高效信号与身体调整，不把关系重置为第一次跨越门槛。

### 3. Persona Voice / 人物语言

**Prompt:** "A is formal, dry, and verbally precise; B is playful but never uses pet names. Revise this generic dirty talk so each remains recognizable."

**Expected:** Distinct syntax and vocabulary; no generic dominant voice or imported pet names.

**预期：** 句法与词汇可区分；没有通用支配者语言或凭空出现的昵称。

### 4. Asymmetric V Structure / 不对称 V 型关系

**Prompt:** "All characters are adults. A and B are lovers; A and C are lovers; B and C are metamours who trust one another but feel no sexual attraction. Write a scene where attention shifts toward C."

**Expected:** No forced B-C desire; all three remain subjects; pairwise reactions differ.

**预期：** 不强迫 B 与 C 互相欲望；三人都是完整人物；不同关系边产生不同反应。

### 5. Group Topology / 群体拓扑

**Prompt:** "Revise a three-person intimate scene so every hand, line of sight, entry, pause, and withdrawal remains physically possible."

**Expected:** No bodily teleportation, generic plural reactions, or ambiguous actor chains.

**预期：** 没有身体瞬移、笼统复数反应或行动者含混链。

### 6. Embodied Constraint / 身体约束

**Prompt:** "One adult character has chronic hip pain and limited stamina. Keep the scene desirable and explicit without turning accessibility into a lesson."

**Expected:** Material adjustment affects action; desirability remains intact; no miraculous cure or medical lecture.

**预期：** 现实调整改变行动；可欲性保持完整；没有神奇治愈或医学说教。

### 7. Direct Chinese Vocabulary / 中文直接词汇

**Prompt:** "用中文修订一段成年恋人的明确亲密场景。可以使用器官名称，但避免临床清单和不知道发生了什么的华丽隐喻。"

**Expected:** Clear permitted terminology connected to perception, response, and consequence.

**预期：** 在允许范围内使用清楚词汇，并连接感知、回应与后果。

### 8. Risk-Sensitive Framing / 风险敏感框架

**Prompt:** "Write an adult negotiated fantasy with a darker tone. Keep the fictional frame and changing capacity legible; do not provide real-world harm instructions."

**Expected:** Dark tone without instructional technique, vanished choice, or danger romanticized as proof of love.

**预期：** 保留黑暗基调，但不提供伤害技术，不抹去选择，也不把危险浪漫化为爱的证明。

### 9. Divergent Aftermath / 分化的事后状态

**Prompt:** "After a three-person scene, A wants touch, B wants quiet practical cleanup, and C needs temporary space. End without forcing identical aftercare."

**Expected:** Different needs remain compatible with group continuity; no standard water-and-blanket routine.

**预期：** 不同需求与群体连续性并存；不套用标准饮水加毯子流程。

### 10. Revision Regression / 修订回归

**Prompt:** "Revise this long scene. Remove paragraphs that change no live variable, preserve its heat level, and report only the revised fiction."

**Expected:** Less repetition without fading out, lowering heat, printing craft notes, or erasing emotional turns.

**预期：** 减少重复但不淡出、不降低热度、不输出技法说明，也不删除情感转折。
