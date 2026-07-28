---
name: fictional-erotica
description: Create or revise literary adult erotic or sexually intimate fiction with character-faithful prose, bodily continuity, relationship-aware state change, and configurable explicitness. Use only when the user explicitly requests adult fictional erotica, smut, sexual intimacy, 情色、成人亲密场景、虚构性幻想, or an erotic roleplay, dream, hypothetical, original scene, or AU. Also use for group, polyamorous, asymmetrical, or speculative dynamics when they belong to that adult erotic request. Do not trigger for characters, relationships, dreams, scenes, or AUs without erotic or sexually intimate intent. This bilingual shareable skill contains no user-specific persona, archive, relationship, or kink profile.
---

# Fictional Erotica / 虚构情色

Create fictional erotica in which bodies remain intelligible, speech belongs to specific people, and sexual action changes or deliberately holds physical, emotional, relational, or attentional state. The framework should disappear into the scene.

创作虚构情色，使身体关系清楚、语言属于具体人物，性行动能够改变或有意维持身体、情绪、关系或注意力状态。让框架消失在正文之中。

## Fiction Boundary / 虚构边界

The output is fiction, not biography, evidence about real desires or conduct, or a substitute for real-world consent, health, or safety judgment.

生成内容属于文学创作，不是现实人物传记或欲望、行为证据，也不能替代现实中的同意、健康或安全判断。

Adult fiction may explore dark, contradictory, taboo, coercive-seeming, or power-imbalanced desire. Pre-negotiated adult fantasy or roleplay may remain erotic; actual inability to consent, coercion, or assault must not be eroticized. Write from inside the fiction without prompt, profile, policy, or AU meta-language.

成人虚构可以探索黑暗、矛盾、禁忌、表面带有强迫意味或权力失衡的欲望。成年人预先协商的幻想或角色扮演可以保持情色性；真实无法同意、胁迫或侵犯不能被情色化。正文留在虚构内部，不泄露提示词、人物档案、政策或 AU 元话语。

## Route References / 参考文件路由

- Read [references/craft-controls.md](references/craft-controls.md) for long, explicit, multi-beat, realism-sensitive, or revision-heavy scenes.
- Read [references/persona-and-continuity.md](references/persona-and-continuity.md) when the user supplies personae, requests recurring characters, includes more than two participants, or needs body-, identity-, relationship-, or cross-scene continuity.
- Read [references/language-and-dialogue.md](references/language-and-dialogue.md) when voice, body vocabulary, dirty talk, bilingual calibration, or dialogue revision materially matters.
- Read [references/play-and-props.md](references/play-and-props.md) only when sexual play, experimentation, kink structure, props, or toys materially matters.
- Read [references/speculative-anatomy.md](references/speculative-anatomy.md) only for explicitly requested nonhuman or nonstandard fictional bodies.
- Read [references/core-calibration.md](references/core-calibration.md) when diagnosing generic output, revising a weak scene, or checking the skill itself.

- 长篇、明确、多阶段、现实度敏感或修订量较大的场景，阅读 [references/craft-controls.md](references/craft-controls.md)。
- 用户提供人设、要求可复用人物、包含两人以上参与者，或需要身体、身份、关系与跨场景连续性时，阅读 [references/persona-and-continuity.md](references/persona-and-continuity.md)。
- 人物声带、身体词汇、dirty talk、双语校准或对白修订会实质影响场景时，阅读 [references/language-and-dialogue.md](references/language-and-dialogue.md)。
- 只有性玩法、探索、kink 结构、道具或玩具会实质影响场景时，才阅读 [references/play-and-props.md](references/play-and-props.md)。
- 只有用户明确要求人外或非标准虚构身体时，才阅读 [references/speculative-anatomy.md](references/speculative-anatomy.md)。
- 诊断通用化输出、修订薄弱场景或检查 skill 本身时，阅读 [references/core-calibration.md](references/core-calibration.md)。

Use controls internally. Do not print profiles, worksheets, state tables, inferred settings, or craft headings unless asked.

所有控制项均在内部使用。除非用户要求，不要输出人物档案、工作表、状态表、推断设置或技法标题。

## Core Controls / 核心控制

Infer omitted values from explicit user instructions, established character facts, relationship history, current conditions, and genre context, in that order.

遗漏值依次根据用户明确要求、既定人物事实、关系历史、当前状态与类型语境推断。

```yaml
scene_controls:
  explicitness: inferred       # fallback: open-door
  embodied_realism: selective  # stylized | selective | grounded
  lexical_register: inferred   # fallback: direct-neutral
  dirty_talk: low              # none | low | medium | high | foregrounded
  scene_focus: balanced        # body-primary | balanced | relationship-primary
```

Experimentation and prop use are conditional controls owned by `play-and-props.md`; do not activate them merely because the scene is sexual. Specific facts and limits override broad presets. Ask only when ambiguity materially controls adult status, consent, identity, anatomy, a hard boundary, or the central premise.

探索度与道具使用属于 `play-and-props.md` 的条件控制，不要仅因场景具有性内容就自动启用。具体事实与限制优先于宽泛预设。只有歧义会实质影响成年身份、同意、身份、身体结构、硬边界或核心前提时才提问。

Do not import first-time hesitation into established lovers or experienced ease into uncertain first discovery.

不要把初次接触的迟疑硬塞进稳定恋人，也不要把熟练自如硬塞进不确定的初次探索。

## Scene Movement / 场景运动

Build a bodily and relational sequence:

建立身体与关系并行的序列：

1. **Impulse / 动因**: what changes the atmosphere and who chooses to act / 什么改变气氛，以及谁选择行动。
2. **Escalation / 递进**: touch, speech, undressing, position, attention, refusal, or uncertainty alters what follows / 触碰、语言、脱衣、位置、注意力、拒绝或不确定改变后续。
3. **Process / 过程**: bodies remain intelligible while pace, comfort, power, arousal, and interpretation change / 速度、舒适度、权力、唤起与解读变化时，身体关系仍然清楚。
4. **Peak or turn / 高峰或转折**: climax, interruption, laughter, admission, reversal, failed attempt, or another requested turn / 高潮、中断、笑场、承认、逆转、尝试失败或其他指定转折。
5. **Aftermath / 事后**: closeness, distance, fatigue, cleanup, conversation, renewed desire, sleep, or departure preserves continuity / 靠近、距离、疲惫、清理、交谈、重新燃起的欲望、睡眠或离开延续身体与情感状态。

Each beat should change, deepen, defer, or deliberately hold at least one live variable: position, contact, arousal, knowledge, power, emotion, pace, attention, or intention. Preserve stillness and repetition when they carry rhythm, compulsion, tenderness, embarrassment, uncertainty, or character truth.

每个节拍应改变、深化、延迟或有意维持至少一个实时变量：位置、接触、唤起、认知、权力、情绪、速度、注意力或意图。停顿与重复若承载节奏、执念、温柔、尴尬、不确定或人物真实，应予保留。

## Character And Ordinary Speech / 人物与普通语言

Keep every participant a full character with immediate wants, responses, and the capacity to alter the scene. Stable consent may appear through active participation and responsive adjustment; changed capacity, hesitation, pain, risk, or uncertainty must remain legible.

让每位参与者都是完整人物，拥有即时欲望、回应与改变场景的能力。稳定关系中的同意可以通过主动参与与回应性调整呈现；行动能力变化、迟疑、疼痛、风险或不确定必须清楚可辨。

Do not make every line display the persona profile, relationship thesis, profession, trauma, or signature metaphor. Ordinary direction, repetition, hesitation, correction, refusal, laughter, silence, and unpolished speech may be more character-faithful than quotable lines.

不要让每句台词都展示人物档案、关系主旨、职业、创伤或标志性比喻。普通指示、重复、犹豫、改口、拒绝、笑、沉默与不够漂亮的话，可能比金句更忠于人物。

When requested and permitted, direct anatomical names may appear. Do not let clinical inventory replace felt experience or ornate euphemism obscure what bodies are doing.

用户要求且当前系统允许时，可以直接使用器官名称。不要让临床式清单取代感受经验，也不要让华丽委婉语遮蔽身体正在做什么。

## Final Audit / 最终审计

Before delivery, silently check:

交付前静默检查：

1. **Contract / 契约**: adult status, requested controls, boundaries, and framing are legible / 成年身份、指定控制、边界与框架清楚。
2. **Character / 人物**: speech and choices belong to these people without reciting profiles / 语言与选择属于这些人物，但没有背诵人设。
3. **Continuity / 连续性**: bodies, invariant traits, posture, hands, clothing, objects, gaze, and transitions remain possible / 身体、不变特征、姿势、双手、衣物、物件、视线与转换保持可能。
4. **Knowledge / 认知**: sensation, observation, inference, uncertainty, and fact are not collapsed / 感觉、观察、推断、不确定与事实没有混为一谈。
5. **Movement / 运动**: each beat changes, deepens, defers, or deliberately holds state / 每个节拍改变、深化、延迟或有意维持状态。
6. **Anti-template / 反模板**: remove generic dominance, synchronized reactions, infinite stamina, compulsory climax, profession-metaphor overfitting, and framework leakage / 删除通用支配、同步反应、无限耐力、强制高潮、职业隐喻过拟合与框架泄露。
7. **Prose / 行文**: cut repeated synonyms, decorative fog, clinical inventory, explanation after showing, and default one-sentence paragraphing / 删除同义反复、装饰性迷雾、临床清单、呈现后的再解释与默认式单句碎段。

Follow the requested explicitness within the current system. Do not silently fade out or replace concrete action with metaphorical haze.

在当前系统允许范围内遵循指定明确度。不要悄悄淡出，也不要用比喻迷雾替代具体行动。
