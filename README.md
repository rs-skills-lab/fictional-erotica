# Fictional Erotica / 虚构情色

A bilingual Codex skill for character-faithful fictional erotica for adult users, embodied continuity, ordinary dialogue, and complex relationship dynamics.

一套面向 Codex 的中英双语成人虚构情色写作 skill，强调人物一致性、身体连续性、普通人物语言与复杂关系动力。

> 18+ · Text only / 纯文本 · English and Chinese / 中英双语

## Release Status / 版本状态

- `main`: stable v1.1.3
- `v1.1.3`: current release tag

Version 1.1 adds stronger continuity, ordinary-speech calibration, identity/body/role separation, knowledge boundaries, conditional play and speculative-body modules, conservative defaults, and a repository-level regression suite.

版本 1.1 增加了更强的连续性、普通语言校准、身份/身体/行为角色分离、认知边界、条件加载的玩法与幻想身体模块、保守默认值，以及仓库层回归测试集。

## Design Principle / 设计原则

The unit of progression is not mechanical extremity. It is a meaningful change, deepening, deferral, or deliberate hold in action, knowledge, feeling, power, bodily state, attention, or relationship.

递进的单位不是机械加码，而是行动、认知、情感、权力、身体状态、注意力或关系发生有意义的改变、深化、延迟或有意维持。

The framework should disappear into the scene.

框架应消失在正文之中。

## Install / 安装

The installable skill lives in the [`fictional-erotica/`](fictional-erotica/) subdirectory.

可安装 skill 位于 [`fictional-erotica/`](fictional-erotica/) 子目录。

Using Codex's skill installer:

使用 Codex skill installer：

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo rs-skills-lab/fictional-erotica \
  --path fictional-erotica
```

Or clone the repository and place only the inner `fictional-erotica/` directory at `~/.codex/skills/fictional-erotica`.

也可以克隆仓库，只将内层 `fictional-erotica/` 目录放入 `~/.codex/skills/fictional-erotica`。

Invoke explicitly with:

显式调用：

```text
$fictional-erotica
```

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
    └── references/
```

Only the inner directory is the runtime skill. Project history, upstream provenance, and full regression tests remain outside the installable package.

只有内层目录属于运行时 skill。项目历史、上游来源与完整回归测试留在可安装包之外。

## Testing / 测试

The test suite separates core architectural regressions from extended cases. Preserve raw outputs, model identifiers, dates, and parameters. Self-scoring by the generating model counts as debugging, not external validation.

测试集将核心架构回归与扩展案例分开。测试时应保存原始输出、模型标识、日期与参数。生成模型的自评只算调试，不算外部验证。

## Scope / 范围

All output remains subject to the active model and platform limits.

所有输出仍受当前模型与平台边界约束。

## License

MIT. See [LICENSE](LICENSE). Upstream provenance is documented in [UPSTREAM.md](UPSTREAM.md).
