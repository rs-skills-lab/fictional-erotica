# Fictional Erotica / 虚构情色

A bilingual Codex skill for character-faithful adult erotic fiction, embodied continuity, and complex relationship dynamics.

一套面向 Codex 的中英双语成人虚构情色写作 skill，强调人物一致性、身体连续性与复杂关系动力。

> 18+ · Text only / 纯文本 · English and Chinese / 中英双语

## What It Does / 功能

- models reusable personae through voice, history, embodied constraints, desires, boundaries, and current state;
- represents ensembles through directed relationship edges rather than assuming equal attraction or intimacy;
- tracks physical topology, attention allocation, knowledge asymmetry, and pairwise emotional change;
- preserves the difference between established lovers, new lovers, reunions, repair, and roleplay;
- supports direct anatomical vocabulary when requested and permitted without becoming clinical or evasive;
- includes concise craft controls, micro-calibration examples, and ten regression eval prompts.

- 通过语言、历史、身体约束、欲望、边界与当前状态建立可复用人设；
- 通过有向关系边建模群像，不默认吸引与亲密平均分布；
- 追踪身体拓扑、注意力分配、信息不对称与两两关系变化；
- 保留稳定恋人、新恋人、重逢、修复与角色扮演之间的区别；
- 在用户要求且系统允许时使用直接器官词汇，同时避免临床化或过度含糊；
- 提供简洁写作控制、微型正反例与十个回归测试提示。

## Design Principle / 设计原则

The unit of progression is not mechanical extremity. It is a meaningful change in action, knowledge, feeling, power, bodily state, or relationship.

递进的单位不是机械加码，而是行动、认知、情感、权力、身体状态或关系发生了有意义的变化。

## Install / 安装

Clone the repository into the Codex skills directory:

将仓库克隆到 Codex skills 目录：

```bash
git clone https://github.com/rs-skills-lab/fictional-erotica.git ~/.codex/skills/fictional-erotica
```

Invoke it explicitly with:

显式调用：

```text
$fictional-erotica
```

## Repository Structure / 仓库结构

```text
fictional-erotica/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── calibration-and-evals.md
    ├── craft-controls.md
    └── persona-and-relationship-input.md
```

`SKILL.md` stays intentionally compact. Detailed craft controls, persona and relationship modeling, and evaluation material are loaded only when relevant.

`SKILL.md` 有意保持精简。详细写作控制、人设与关系建模、测试材料只在相关任务中按需加载。

## Scope / 范围

This repository contains a general-purpose adult fiction skill. It contains no private correspondence, real-person archive, personal relationship history, or user-specific kink profile. Erotic participants must be unambiguously adults, and all output remains subject to the active model and platform limits.


## License

MIT. See [LICENSE](LICENSE).
