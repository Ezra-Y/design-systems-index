<div align="center">

# 设计系统索引 🧩

各公司设计系统的外部资源索引——Material、Fluent、Carbon、Polaris、Atlassian、Lightning，以及 design tokens、pattern library、React/RN 设计系统库。

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[English](README.md) · **中文说明**

</div>

---

## 为什么需要它

当你要选一个设计系统来学习、或挑选 React 组件库时，问题不是「token 怎么建」（那是本地 `design-system` skill 的事），而是「**该参考或采用哪个成熟 DS**」。本索引用链接回答这个问题，精选自 awesome-design-systems 与 awesome-react-design-systems。

> 💡 **类型说明**：这是*资源索引*（仅链接）。token 架构方法论有意不在此重复——见你本地的 `design-system` skill。

## 内容

五个分类：

- 🏢 主要公司设计系统 — Material、Fluent、Carbon、Polaris、Atlassian、Lightning…
- 🎨 设计 tokens 资源
- 📚 pattern library 资源
- ⚛️ React 设计系统库
- 📱 React Native 设计系统库

溢出条目见 `references/more.md`。

## 安装

```bash
git clone https://github.com/Ezra-Y/design-systems-index.git ~/.claude/skills/design-systems-index
```

然后重启 Claude Code（或跑 `/reload-plugins`）。

## 用法

在「参考现有设计系统 / 找各公司 DS / design tokens / component library / React 设计系统」等表述时自动触发。示例：

```
我想参考几个大公司的设计系统
Which React design system should I adopt for a SaaS dashboard?
给我一些 design tokens 的工具和规范
```

## 结构

```
design-systems-index/
├── SKILL.md              # 5 类索引（≤100 行）
├── references/
│   └── more.md           # 溢出条目
└── README.md
```

## 来源与致谢

内容精选、精简自以下两个 awesome-list（请给原仓库点 star）：

- [klaufel/awesome-design-systems](https://github.com/klaufel/awesome-design-systems)
- [jbranchaud/awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems)

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y
