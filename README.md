<div align="center">

# Design Systems Index 🧩

A curated external index of design systems — Material, Fluent, Carbon, Polaris, Atlassian, Lightning, plus design tokens, pattern libraries, and React/RN DS libraries.

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[中文说明](README.zh-CN.md) · English

</div>

---

## Why

When you're choosing a design system to learn from, or picking a React component library, the question isn't "how do I build tokens" (that's the local `design-system` skill's job) — it's "**which mature DS should I study or adopt?**". This index answers that with links, distilled from [awesome-design-systems](https://github.com/klaufel/awesome-design-systems) and [awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems).

> 💡 **Type note:** This is a *resource index* (links only). Token-architecture methodology is intentionally NOT duplicated here — see your local `design-system` skill for that.

## What's inside

Each entry is `Name (link) — one-line note`. `SKILL.md` is a **dispatch index**: 2–3 top picks per category inline, with the full list in per-category reference files (loaded on demand):

- 🏢 Major company DS — Material, Fluent, Carbon, Polaris, Atlassian, Lightning… → `references/major-company-systems.md`
- 🎨 Design token resources → `references/design-tokens.md`
- 📚 Pattern library resources → `references/pattern-libraries.md`
- ⚛️ React DS libraries → `references/react-ds-libraries.md`
- 📱 React Native DS libraries → `references/react-native-ds-libraries.md`

## Install

```bash
git clone https://github.com/Ezra-Y/design-systems-index.git ~/.claude/skills/design-systems-index
```

Then restart Claude Code (or run `/reload-plugins`).

## Use

Auto-triggers on phrases like "参考现有设计系统 / 找各公司 DS / design tokens / component library / React 设计系统". Examples:

```
I want to reference a few large companies' design systems
Which React design system should I adopt for a SaaS dashboard?
给我一些 design tokens 的工具和规范
```

## Structure

```
design-systems-index/
├── SKILL.md              # dispatch index: 2-3 picks per category + pointers
├── references/           # per-category full lists (loaded on demand)
│   ├── major-company-systems.md
│   ├── design-tokens.md
│   ├── pattern-libraries.md
│   ├── react-ds-libraries.md
│   └── react-native-ds-libraries.md
└── README.md
```

## Sources & Attribution

Data sourced and curated from the following two awesome-lists — please star the originals:

- [klaufel/awesome-design-systems](https://github.com/klaufel/awesome-design-systems) — design systems, design tokens, and pattern libraries.
- [jbranchaud/awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems) — React / React Native design-system component libraries.

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

## License

[MIT](LICENSE) — © Ezra-Y
