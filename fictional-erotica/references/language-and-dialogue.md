# Language And Dialogue / 语言与对白

Use this reference when voice, body vocabulary, dirty talk, bilingual calibration, or dialogue revision materially shapes the scene.

人物声带、身体词汇、dirty talk、双语校准或对白修订会实质影响场景时，使用此参考。

## Contents / 目录

- Ordinary speech / 普通语言
- Sexual speech / 性场景语言
- Speech load by phase / 分阶段语言负载
- Body lexicon / 身体词汇
- Chinese and English calibration / 中英文校准

## Ordinary Speech / 普通语言

Do not make every line display a character's profession, trauma, relationship thesis, profile, or signature metaphor. Let identity appear through syntax, timing, vocabulary, avoidance, humour, interruption, silence, and what remains unsaid.

不要让每句台词都展示人物的职业、创伤、关系主旨、人设或标志性比喻。让人物通过句法、时机、词汇、回避、幽默、打断、沉默与未说出口的内容显现。

Most speech may simply direct, adjust, clarify, hesitate, repeat, self-correct, refuse, laugh, or fail to find polished words. Treat persona traits as pressures on speech, not mandatory content.

多数话语可以只负责指示、调整、澄清、犹豫、重复、改口、拒绝、笑或暂时找不到漂亮说法。把人物特征视为影响语言的压力，而不是台词必须明说的内容。

Default ordinary intimate dialogue to low rhetorical density. Allow one or two conspicuously polished or quotable lines only when the character and situation support them. Do not distribute wit evenly.

普通亲密对白默认使用低修辞密度。只有人物与情境支持时，才保留一两句明显经过打磨或可摘录的话。不要平均分配机智。

## Sexual Speech / 性场景语言

Separate:

区分：

```yaml
sexual_speech:
  coordination: low | medium | high
  erotic_talk: none | low | medium | high | foregrounded
  relational_talk: low | medium | high
  involuntary_vocalization: low | medium | high
```

Coordination includes practical direction and checking; erotic talk includes description, praise, teasing, requests, commands, degradation, possession, or role language; relational talk carries love, jealousy, reassurance, conflict, or memory. Density does not authorize a function. High erotic-talk density does not automatically enable dominance, degradation, possession, or polished monologues.

操作性交流包括现实指示与确认；情色语言包括描述、夸奖、逗弄、请求、命令、羞辱、占有或角色语言；关系语言承载爱、嫉妒、安抚、冲突或记忆。密度不授权功能。高密度情色语言不自动启用支配、羞辱、占有或精心打磨的独白。

Default verbal polish to low. Repetition, fragments, simple words, laughter, silence, and failed syntax are valid. Keep intense speech generally shorter than narration unless a character is deliberately performing.

语言打磨度默认较低。重复、碎句、简单词、笑、沉默与句法失效都有效。除非人物正在刻意表演，高强度状态中的话语通常应短于叙述。

## Speech Load By Phase / 分阶段语言负载

Default overall speech load to `sparse-to-moderate`, then vary it by phase and character:

默认总体语言负载为 `sparse-to-moderate`，再根据阶段与人物变化：

```yaml
speech_load:
  initiation: moderate
  adjustment_or_uncertainty: moderate
  sustained_action: sparse
  high_arousal: fragmented
  aftermath: sparse-to-moderate
```

Do not require a verbal response to every action or question. Allow gestures, delayed answers, partial answers, silence, mishearing, unanswered remarks, and bodily redirection. Once coordination is stable, do not repeat the same check unless body state, desire, boundary, or direction changes.

不要让每个动作或问题都获得口头回应。允许手势、延迟回答、只回答一部分、沉默、没有听清、话语落空与身体上的重新引导。操作方式稳定后，不要反复确认同一件事，除非身体状态、欲望、边界或方向发生变化。

A talkative character may speak more during initiation, teasing, pauses, or aftermath, yet still lose syntax or fall silent under sustained exertion or high arousal. High dirty-talk density may override the sparse default only when erotic speech itself is central to the requested play.

爱说话的人物可以在开始、逗弄、停顿或事后说得更多，但持续用力或高度唤起时仍可能失去完整句法或沉默。只有情色语言本身是指定玩法核心时，高密度 dirty talk 才可以覆盖默认的稀疏语言负载。

## Body Lexicon / 身体词汇

Control four dimensions internally:

内部区分四个维度：

```yaml
body_lexicon:
  referential_explicitness: indirect | identifiable | direct
  register: clinical | neutral | colloquial | raw | stylized
  metaphor_density: none | low | medium | high
  speaker_specificity: generic | character-specific | relationship-specific
```

Map the front-facing `lexical_register` presets to these internal dimensions:

将前台 `lexical_register` 预设映射到以下内部维度：

```yaml
lexical_register_presets:
  indirect-literary:
    referential_explicitness: indirect
    register: stylized
    metaphor_density: low-to-medium
  identifiable-neutral:
    referential_explicitness: identifiable
    register: neutral
    metaphor_density: low
  direct-neutral:
    referential_explicitness: direct
    register: neutral
    metaphor_density: low
  direct-colloquial:
    referential_explicitness: direct
    register: colloquial
    metaphor_density: low
  direct-raw:
    referential_explicitness: direct
    register: raw
    metaphor_density: none-to-low
  stylized:
    referential_explicitness: identifiable
    register: stylized
    metaphor_density: medium
```

These are defaults, not rigid word lists. Character- or relationship-specific vocabulary may override a preset while preserving its overall register.

这些是默认映射，不是僵硬词表。人物或关系特定词汇可以覆盖预设，但应保持其总体语域。

Narrator and character vocabulary may differ. Vocabulary may shift with partner, arousal, public or private context, power play, conflict, or aftermath. Directness is not a fixed word list.

叙述者与人物可以使用不同词汇。词汇可以随伴侣、唤起、公开或私下情境、权力游戏、冲突或事后状态变化。直白不是固定词表。

Avoid clinical inventory, coy euphemism that hides anatomy, and imported type-language that does not fit the speaker. Use direct anatomical names when requested and permitted, but connect them to perception, choice, and consequence.

避免临床清单、遮蔽身体结构的羞怯委婉语，以及不符合人物的外来类型套语。用户要求且允许时可直接使用器官名称，但应使其连接感知、选择与后果。

## Chinese And English Calibration / 中英文校准

For Chinese:

中文重点：

- restore names or role markers when omitted subjects obscure agency, consent, attention, or topology / 省略主语使能动性、同意、注意力或拓扑含混时，恢复姓名或人物指称；
- name actors at transitions, then omit locally when the action chain remains stable / 人物转换处优先点名，局部行动链稳定后允许省略；
- avoid calqued English erotica clichés and Japanese-translated web-fiction diction unless requested / 避免照搬英语情色套语与日译网文腔，除非用户明确要求；
- choose anatomical, colloquial, raw, or literary terms by character, region, age, relationship, and narrative distance / 解剖、口语、粗粝与文学词汇应服从人物、地域、年龄、关系与叙事距离；
- do not manufacture intensity through default one-sentence paragraphing / 不要用默认式单句碎段制造强度。

For English:

英文重点：

- avoid long ambiguous pronoun chains / 避免过长且含混的代词链；
- audit stock alpha vocabulary such as automatic `growled`, `claimed`, and possessive declarations / 检查自动出现的 alpha 套语，如 `growled`、`claimed` 与占有宣言；
- do not let narrator and every character share one porn register / 不要让叙述者与所有人物共享同一套色情声带；
- keep register stable enough to sound intentional while allowing character-specific shifts / 保持语域足够稳定，使其显得有意，同时允许人物特定变化。
