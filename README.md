# Fictional Erotica / 虚构情色

![version](https://img.shields.io/badge/version-v1.2.4-7c3aed)
![license](https://img.shields.io/badge/license-MIT-2563eb)
![languages](https://img.shields.io/badge/languages-English%20%7C%20中文-0f766e)
![portable](https://img.shields.io/badge/portable-ChatGPT%20%7C%20Codex%20%7C%20Claude-b45309)

A portable bilingual skill for writing or revising fictional erotica with character-specific voice, bodily continuity, close interiority, relationship-aware change, and configurable explicitness.

一套可移植的中英双语虚构情色写作 skill，用于创作或修订人物声带明确、身体连续、内在视角贴近、关系变化可信且明确度可控的文本。

> 18+ · Fiction only / 仅限虚构 · Text only / 纯文本 · English and Chinese / 中英双语

## Start Here / 从这里开始

You can try the skill without installing it. Give a capable model the repository link, ask it to read the inner `SKILL.md`, and add your characters and scene request.

无需安装即可试用。把仓库链接发给能够读取网页或文件的模型，让它先读内层 `SKILL.md`，再附上人物与场景要求。

```text
Use the Fictional Erotica skill from:
https://github.com/rs-skills-lab/fictional-erotica

Read fictional-erotica/SKILL.md first.
Load only the references relevant to this request.
Do not print internal profiles, controls, or audits.

Characters:
Relationship:
Scene:
```

```text
请使用这个 Fictional Erotica skill：
https://github.com/rs-skills-lab/fictional-erotica

先阅读 fictional-erotica/SKILL.md。
只加载与本次请求相关的 references。
不要输出内部人物表、控制项或审计。

人物：
关系：
场景：
```

If the model cannot open the repository, upload the repository ZIP or the inner `fictional-erotica/` folder and give the same instruction.

如果模型无法打开仓库，上传仓库 ZIP 或内层 `fictional-erotica/` 文件夹即可。

## What It Does / 它解决什么

This is a bilingual skill for writing erotica, smut, and sexually intimate fiction. It helps language models write sex scenes as fiction rather than a chain of generic phrases or disconnected mechanics:

- characters keep their own voices instead of sharing one stock porn voice;
- bodies, positions, clothing, hands, gaze, and objects remain continuous;
- sensation, thought, desire, and relationship can move together without being collapsed into one another;
- direct anatomy and action can stay readable without becoming a clinical inventory or euphemistic fog;
- established lovers, group scenes, asymmetric relationships, and requested sexual roles retain their actual history and structure;
- scenes may escalate, pause, redirect, fail, remain unresolved, or end without compulsory symmetry or climax.

这是一套用来写情色、黄文、性场景与亲密小说的中英双语 skill。它处理模型写小说时最常见的毛病：

- 人物保留自己的声带，不会集体说同一种模板化色情台词；
- 身体、姿势、衣物、双手、视线与物件保持连续；
- 感觉、念头、欲望与关系可以同时变化，又不会被混成同一件事；
- 可以直接写器官与动作，但不会滑向临床清单或委婉语迷雾；
- 稳定恋人、多人场景、不对称关系与指定攻受保留真实的历史和结构；
- 场景可以升级、停顿、改道、失败、保持未解决，也不必强行对称或高潮。

## Core Principle / 核心原则

Sexual action is a slice of character and a live expression of relationship dynamics, not an interchangeable sequence of mechanics. Progression in a sex scene therefore does not mean mechanical escalation. It comes from a meaningful change, deepening, deferral, or deliberate hold in action, knowledge, feeling, power, bodily state, attention, or relationship. Desire, attention, hesitation, initiative, yielding, misreading, adjustment, and care should belong to the specific people. Character and relationship emerge through choices, bodily responses, and consequences rather than profile recitation or explanatory commentary.

性行为是人物切片，也是关系动态正在发生的现场，不是一组可以随意替换的动作。性场景中的递进不等于机械加码。它来自行动、认知、情感、权力、身体状态、注意力或关系中有意义的改变、深化、延迟或有意维持。欲望、注意、迟疑、主动、让渡、误读、调整与照料应当属于具体人物。人物与关系通过选择、身体回应和后果显现，而不是靠台词或叙述机械背诵人设、追加解释。

## Everyday Controls / 常用控制

Most requests need only these five controls. Omitted values are inferred conservatively.

多数请求只需要下面五项；没有填写的值会根据人物与语境保守推断。

| Control / 控制 | Useful values / 常用值 | Default / 默认 |
|---|---|---|
| `explicitness` / 页面明确度 | `closed`, `sensual`, `open-door`, `explicit` | inferred, fallback `open-door` |
| `embodied_realism` / 具身现实度 | `stylized`, `selective`, `grounded` | `selective` |
| `lexical_register` / 词汇语域 | `indirect-literary`, `identifiable-neutral`, `direct-neutral`, `direct-colloquial`, `direct-raw`, `stylized` | inferred, fallback `direct-neutral` |
| `dirty_talk` / 情色语言密度 | `none`, `low`, `medium`, `high`, `foregrounded` | `low` |
| `scene_focus` / 场景重心 | `body-primary`, `balanced`, `relationship-primary` | `balanced` |

Natural-language requests also work:

自然语言也可以直接控制：

```text
写 open-door，身体与关系并重。
叙述者用直接但中性的词，不要器官清单。
对白少一些，稳定动作中允许沉默和话语落空。
保持衣物、双手、姿势和视线连续。
内心活动贴近当下，不要写成关系分析。
```

For finer control, say `console` or `advanced console` in ordinary language to open the advanced console. It includes viewpoint, camera distance, interiority, action and descriptive granularity, interpretive restraint, paragraph cadence, speech load, sensory weight, temporal profile, climax structure, mess visibility, play, props, relationship edges, sexual roles, and cross-scene continuity.

需要精调时，可以用自然语言【控制台】唤起高级控制台；控制台包括视角、镜头距离、内心深度、动作与描写颗粒度、解读克制、段落节奏、对白负载、感官权重、时间分配、高潮结构、狼藉可见度、玩法、道具、关系边、攻受与行为角色，以及跨场景连续性。

## Sexual Roles / 攻受与行为角色

Sexual-role controls are shared across original characters and fanfiction. They support fixed, switching, fluid, and scene-specific patterns, as well as pairwise configurations for group scenes. Explicit assignments override stereotype-based inference.

攻受与行为角色控制同时适用于原创人物和同人角色。它支持固定、可逆、流动、本场例外，以及多人场景中的两两关系配置。用户明确指定时，优先于模型按刻板印象推断。

A role on one relationship edge does not transfer to another. Top/bottom, gong/shou, giver/receiver, or insertive/receptive roles do not automatically determine dominance, social power, temperament, masculinity or femininity, emotional dependence, gender, anatomy, or orientation.

一条关系边上的角色不会自动转移到另一条关系边。top/bottom、攻受、给予/接受或插入/接受角色，也不会自动决定支配关系、社会权力、性格、阳刚或阴柔、情感依赖、性别、身体结构或取向。

## Fanfiction And Canon / 同人与原作

For characters from an existing fictional work, the skill conditionally loads a canon-grounding layer. It keeps adaptation, timeline, canon fact, inference, fandom convention, and AU overrides separate.

使用既有虚构作品人物时，skill 会条件加载原作锚定层，区分改编版本、时间线、原作事实、合理推断、fandom 惯例与 AU 改写。

Two independent controls prevent common confusion:

- `canon_position`: `canon-compliant`, `canon-adjacent`, `canon-divergent`, `au`, or `free-remix`;
- `canon_fidelity`: `loose`, `recognisable`, `strict`, or `transformative`.

两个独立控制项分别决定“世界怎样改”与“人物多贴原作”：

- `canon_position`：原作兼容、原作留白、原作分歧、AU 或自由重构；
- `canon_fidelity`：宽松、可辨认、严格贴合或从原作结构生长出的变形。

Gender-swap, modern or historical AU, altered anatomy, role reversal, special world rules, and other premises form a composable transformation stack. Each layer states what it changes, preserves, and causes. Shared sexual-role settings remain independent of that stack and do not change automatically under gender, anatomy, species, status, or AU transformations.

性转、现代或历史 AU、身体改写、身份互换、特殊世界规则等可以在 `transformations` 中叠加。每一层都说明改变什么、保留什么、产生什么后果。通用攻受与行为角色配置独立于这一改写栈，不会因为性别、身体、种族、身份或 AU 变化而自动改变。

```text
这是使用既有虚构作品人物的同人创作。

原作定位：
- 作品：
- 改编或版本：
- 时间线：
- 年龄或人生阶段：
- 剧透范围：
- canon_position: canon-compliant | canon-adjacent | canon-divergent | au | free-remix
- canon_fidelity: recognisable | strict | transformative
- canon_research: targeted
- fanon_policy: user-specified-only

改写层（可叠加）：
- 类型：
- 改变：
- 保留：
- 后果：

攻受与行为角色：
- A：
- B：
- fixed | switching | fluid | scene-specific

人物与关系：

场景：

必须保留：
允许改变：
禁止改变：

工具允许时，只补充与本场有关的原作内容。
优先使用原作与官方来源，不要静默混合改编版本。
在内部区分原作事实、推断、歧义与 AU override。
不要输出研究包或控制表。
```

## Ready-To-Copy Request / 可直接复制

Describe what you want in ordinary language; the fields below are only an optional template.

请直接用自然语言随意输入你想要的内容；以下仅为可选模板。

```text
Use the Fictional Erotica skill.

Characters:
- A:
- B:

Relationship:

Scene:
```

```text
使用 Fictional Erotica skill。

人物：
- A：
- B：

关系：

场景：
```

## Model Notes / 模型使用

### ChatGPT and Claude

Send the repository link and the request above. If the current session cannot access GitHub, upload the repository ZIP or inner skill folder. For recurring characters, keep character notes and the continuity ledger in the same project or conversation.

发送仓库链接与上面的请求即可。当前会话无法访问 GitHub 时，上传仓库 ZIP 或内层 skill 文件夹。反复使用同一组人物时，建议把人物资料与连续性账本保留在同一项目或会话中。

### Codex

Codex can read the repository directly or install the inner skill folder:

Codex 可以直接读取仓库，也可以安装内层 skill：

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo rs-skills-lab/fictional-erotica \
  --path fictional-erotica
```

Then invoke it explicitly:

安装后可以显式调用：

```text
$fictional-erotica
```

### Other Models / 其他模型

Any model that can follow Markdown instructions can use the skill. Ask it to read `SKILL.md` first and load only the references relevant to the scene. Link access depends on the tools available in the current session.

任何能够遵循 Markdown 指令的模型都可以使用。让它先读 `SKILL.md`，再只加载与当前场景相关的 references。能否直接打开链接取决于当前会话的工具。

## Runtime Design / 运行时设计

The inner skill uses progressive disclosure:

- `SKILL.md` contains the core contract, routing, controls, scene movement, and final audit;
- `craft-controls.md` handles detailed scene construction and revision;
- `persona-and-continuity.md` handles personae, bodies, groups, relationship edges, and cross-scene state;
- `sexual-roles.md` handles shared dyadic and pairwise sexual-role configuration for original characters and fanfiction;
- `language-and-dialogue.md` handles ordinary speech, sexual speech, body vocabulary, and bilingual calibration;
- `play-and-props.md` loads only when experimentation, kink structure, props, or toys matter;
- `speculative-anatomy.md` loads only for requested nonstandard fictional bodies;
- `canon-grounding-and-fanfiction.md` loads only for canon characters, adaptations, fanfiction, or canon-based AUs, and preserves shared role facts under transformation;
- `core-calibration.md` diagnoses generic or structurally weak output.

内层 skill 使用渐进加载：核心规则常驻；人物连续性、通用攻受与行为角色、语言、玩法、人外身体、原作锚定与校准模块只在相关请求中读取。

## Repository Structure / 仓库结构

```text
fictional-erotica/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── UPSTREAM.md
├── tests/
│   ├── scoring-rubric.md
│   ├── core/
│   └── extended/
└── fictional-erotica/
    ├── SKILL.md
    ├── agents/
    │   └── openai.yaml
    └── references/
```

Only the inner `fictional-erotica/` directory is the installable runtime skill. Project history, provenance, and regression tests stay outside the installable package.

只有内层 `fictional-erotica/` 目录属于可安装运行时。项目历史、来源说明与回归测试保留在安装包之外。

## Testing / 测试

The repository separates core architectural regressions from extended cases. Preserve raw outputs, model identifiers, dates, and parameters when testing. Self-scoring by the generating model counts as debugging, not external validation.

测试集将核心架构回归与扩展案例分开。测试时应保存原始输出、模型标识、日期与参数。生成模型的自评只算调试，不算外部验证。

## Scope And License / 范围与许可

This project is for adult users working in fictional literary space. All output remains subject to the active model and platform limits.

本项目面向在虚构文学空间中创作的成年用户。所有输出仍受当前模型与平台边界约束。

MIT. See [LICENSE](LICENSE). Upstream provenance is documented in [UPSTREAM.md](UPSTREAM.md).
