# Design Systems Index 🧩

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](https://github.com/Ezra-Y/design-systems-index)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

A curated **external index of design systems** — major companies' DS (Material, Fluent, Carbon, Polaris, Atlassian, Lightning…), design-token tooling, pattern libraries, and React / React Native DS component libraries. For **referencing existing design systems**.

各公司设计系统的**外部资源索引**——主要公司 DS（Material/Fluent/Carbon/Polaris/Atlassian/Lightning 等）、design tokens 工具、pattern library、React 与 RN 设计系统组件库。用于**参考现有设计系统**。

---

## Why / 为什么需要它

When you're choosing a design system to learn from, or picking a React component library, the question isn't "how do I build tokens" (that's the local `design-system` skill's job) — it's "**which mature DS should I study or adopt?**". This index answers that with links, distilled from [awesome-design-systems](https://github.com/klaufel/awesome-design-systems) and [awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems).

当你要选一个设计系统来学习、或挑选 React 组件库时，问题不是「token 怎么建」（那是本地 `design-system` skill 的事），而是「**该参考或采用哪个成熟 DS**」。本索引用链接回答这个问题，精选自 awesome-design-systems 与 awesome-react-design-systems。

> 💡 **Type note / 类型说明**: This is a *resource index* (links only). Token-architecture methodology is intentionally NOT duplicated here — see your local `design-system` skill for that.

---

## What's inside / 内容

Five categories:

五个分类：

- 🏢 **主要公司设计系统 / Major company DS** — Material, Fluent, Carbon, Polaris, Atlassian, Lightning…
- 🎨 **设计 tokens 资源 / Design token resources**
- 📚 **pattern library 资源**
- ⚛️ **React 设计系统库 / React DS libraries**
- 📱 **React Native 设计系统库 / RN DS libraries**

Extras in `references/more.md`. 溢出条目见 `references/more.md`。

---

## Install / 安装

### Claude Code (skill)

```bash
git clone https://github.com/Ezra-Y/design-systems-index.git ~/.claude/skills/design-systems-index
```

Then restart Claude Code (or run `/reload-plugins`).

### As a plugin

```
/plugin marketplace add Ezra-Y/design-systems-index
/plugin install design-systems-index@design-systems-index
```

---

## Use / 用法

Auto-triggers on phrases like "参考现有设计系统 / 找各公司 DS / design tokens / component library / React 设计系统". Examples:

在「参考现有设计系统 / 找各公司 DS / design tokens / component library / React 设计系统」等表述时自动触发。示例：

```
我想参考几个大公司的设计系统
Which React design system should I adopt for a SaaS dashboard?
给我一些 design tokens 的工具和规范
```

---

## Structure / 结构

```
design-systems-index/
├── SKILL.md              # 5 类索引（≤100 行）
├── references/
│   └── more.md           # 溢出条目
└── README.md
```

---

## Sources & Attribution / 来源与致谢

Curated and condensed from (please star the originals):

- [klaufel/awesome-design-systems](https://github.com/klaufel/awesome-design-systems)
- [jbranchaud/awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems)

More awesome lists at [sindresorhus/awesome](https://github.com/sindresorhus/awesome).

---

## License

[MIT](LICENSE) — © Ezra-Y
