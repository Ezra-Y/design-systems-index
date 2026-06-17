<div align="center">

# 设计系统索引 🧩

各公司设计系统的外部资源索引——Material、Fluent、Carbon、Polaris、Atlassian、Lightning，以及 design tokens、pattern library、React/RN 设计系统库。

[![Made for Claude Code](https://img.shields.io/badge/Made%20for-Claude%20Code-blueviolet?style=flat-square)](https://docs.claude.com/en/docs/claude-code)
[![Type: Resource Index](https://img.shields.io/badge/Type-Resource%20Index-2980b9?style=flat-square)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](LICENSE)

[English](README.md) · 中文

</div>

---

## 为什么需要它

当你要选一个设计系统来学习、或挑选 React 组件库时，问题不是「token 怎么建」（那是本地 `design-system` skill 的事），而是「**该参考或采用哪个成熟 DS**」。本索引用链接回答这个问题，精选自 awesome-design-systems 与 awesome-react-design-systems。

> 💡 **类型说明**：这是*资源索引*（仅链接）。token 架构方法论有意不在此重复——见你本地的 `design-system` skill。

## 内容

每个条目为「名称（链接）— 一句话说明」。`SKILL.md` 是**调度索引**：每类 2–3 条精选内联，完整列表在按分类的 reference 文件（按需读取 / loaded on demand）：

- 🏢 主要公司设计系统 — Material、Fluent、Carbon、Polaris、Atlassian、Lightning… → `references/major-company-systems.md`
- 🎨 设计 tokens 资源 → `references/design-tokens.md`
- 📚 pattern library 资源 → `references/pattern-libraries.md`
- ⚛️ React 设计系统库 → `references/react-ds-libraries.md`
- 📱 React Native 设计系统库 → `references/react-native-ds-libraries.md`

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
├── SKILL.md              # 调度索引：每类 2-3 精选 + 指针
├── references/           # 按分类的完整列表（按需读取）
│   ├── major-company-systems.md
│   ├── design-tokens.md
│   ├── pattern-libraries.md
│   ├── react-ds-libraries.md
│   └── react-native-ds-libraries.md
└── README.md
```

## 来源与致谢

本 skill 的数据精选、整理自以下两个 awesome-list——建议给原仓库点 star：

- [klaufel/awesome-design-systems](https://github.com/klaufel/awesome-design-systems) — 设计系统、design tokens、pattern library 等。
- [jbranchaud/awesome-react-design-systems](https://github.com/jbranchaud/awesome-react-design-systems) — React / React Native 设计系统组件库。

更多 awesome 列表见 [sindresorhus/awesome](https://github.com/sindresorhus/awesome)。

## License

[MIT](LICENSE) — © Ezra-Y
