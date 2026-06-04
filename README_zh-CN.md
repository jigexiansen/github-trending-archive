<div align="center">

# 📡 GitHub Trending 归档

**开源世界每天都在变，这里把每一天最值得关注的那一刻留下来。**

[![报告校验](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml/badge.svg)](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml)
[![报告数量](https://img.shields.io/badge/报告-10份-7b2fff.svg)](#-浏览报告)
[![最近更新](https://img.shields.io/badge/最近更新-2026--06--04-ff006e.svg)](https://jigexiansen.github.io/github-trending-archive/reports/2026/06/04.html)
[![许可证: MIT](https://img.shields.io/badge/许可证-MIT-00f5d4.svg)](LICENSE)

[English](README.md) · [在线浏览 →](https://jigexiansen.github.io/github-trending-archive/)

</div>

---

GitHub Trending 每 24 小时重置一次。那些今天备受瞩目的项目，明天可能就消失在信息流里。这个归档把每天排名前 10 的仓库做成独立的 HTML 快照，永久保存在这里——每份报告都有不一样的视觉风格，打开即看，无需依赖任何服务。

不需要数据库，不需要 API，只是一个装满 HTML 文件的文件夹，在线打开或下载到本地都能用。

<div align="center">

**→ [浏览所有报告](https://jigexiansen.github.io/github-trending-archive/)**

</div>

---

## ✨ 每份报告包含什么

每个 HTML 文件完全独立，包含：

| | |
|---|---|
| 🏆 **前 10 名仓库** | 按今日新增 Star 排序——看的是当天势头，不是历史积累 |
| ⭐ **Star 速度条** | 直观对比各项目今天有多热 |
| 🗺️ **语言分布图** | 按今日 Star 权重聚合，不是项目数量 |
| 💡 **趋势洞察** | 对当天数据的简短解读，提炼背后的主题 |
| 🎨 **独特的视觉设计** | 每份报告都有自己的风格，每天打开都有新鲜感 |
| 📦 **零依赖** | 今天打开能用，十年后打开还能用 |

---

## 📂 浏览报告

<details open>
<summary><strong>2026 年 6 月</strong> — 4 份报告</summary>

| 日期 | 当日榜首 | 亮点 |
|------|---------|------|
| [2026-06-04](https://jigexiansen.github.io/github-trending-archive/reports/2026/06/04.html) | headroom +3,530⭐ | 十席中九席锁定 AI 基础设施，上下文压缩与 Agent 框架双引擎主导今日热榜 |
| [2026-06-03](https://jigexiansen.github.io/github-trending-archive/reports/2026/06/03.html) | markitdown +3,618⭐ | 大模型工程化基础设施强势占榜 · Token 压缩与记忆 API 同步爆发 · Python 独揽今日 75% 热度 |
| [2026-06-02](https://jigexiansen.github.io/github-trending-archive/reports/2026/06/02.html) | MoneyPrinterTurbo +3,375⭐ | Python 独占今日 72% 热度 · AI 视频生成与文档工具同步爆发 · 经典「动手学」仓库再度燃起 |
| [2026-06-01](https://jigexiansen.github.io/github-trending-archive/reports/2026/06/01.html) | markitdown +2,798⭐ | Python 占据今日 73% 星标 · 文档转换与 AI 工具链主导榜单 · 生产级 AI 基础设施迁移加速 |

</details>

<details open>
<summary><strong>2026 年 5 月</strong> — 6 份报告</summary>

| 日期 | 当日榜首 | 亮点 |
|------|---------|------|
| [2026-05-31](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/31.html) | MoneyPrinterTurbo +2,768⭐ | AI 工具链聚焦短视频与文档处理 · Python 独揽 65% 今日星标 · Rust 系统感知崛起 |
| [2026-05-30](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/30.html) | MoneyPrinterTurbo +3,567⭐ | AI 效率工具双线爆发 · 反 AI 套话浪潮持续 · Python 主导 AI 生态 |
| [2026-05-29](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/29.html) | MoneyPrinterTurbo +4,698⭐ | AI 工具链多层爆发 · 反 AI 套话浪潮持续 · 技能框架生态扩张 |
| [2026-05-28](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/28.html) | Understand-Anything +4,465⭐ | 反 AI 套话浪潮 · Skills 生态持续爆发 |
| [2026-05-27](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/27.html) | Understand-Anything +4,697⭐ | Skills 生态首次爆发 · Anthropic 插件官方入榜 |
| [2026-05-26](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/26.html) | DeepSeek-TUI +5,787⭐ | AI Agent 基础设施生产化 · 终端原生工具崛起 |

</details>

---

## ⚙️ 报告是怎么生成的

每天，[Claude Code](https://claude.ai/code) 会抓取 `github.com/trending`，按今日 Star 数排列前 10，提炼每个项目的中英双语描述，生成视觉报告并推送到这里。

数据来源于 GitHub 真实页面，不估算，不捏造。如果某个数字看起来不对，要么是 GitHub 当时就那样，要么是个值得报告的 bug。

```
抓取 → 排序 → 描述 → 可视化 → 定制风格 → 归档
```

---

## 🚀 本地使用

```bash
git clone https://github.com/jigexiansen/github-trending-archive
cd github-trending-archive

# 直接打开任意报告
open reports/2026/05/28.html
```

不需要安装，不需要配置，直接打开。

---

## 🤝 参与贡献

发现数据有误？链接失效？描述偏差？
→ 提一个[数据纠错 Issue](../../issues/new?template=data-correction.md)——数据准确是这个项目最重要的事。

对项目有想法或建议？
→ 来 [Discussions](../../discussions) 聊聊，欢迎任何想法。

---

## 📄 许可证

[MIT](LICENSE)，随便用。

数据来源：[github.com/trending](https://github.com/trending) · 由 [Claude Code](https://claude.ai/code) 生成
