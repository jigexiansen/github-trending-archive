<div align="center">

# 📡 GitHub Trending Archive

**A permanent, beautiful record of what the open source world cared about each day.**

[![Validate Reports](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml/badge.svg)](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml)
[![Reports](https://img.shields.io/badge/Reports-3-7b2fff.svg)](#-browse)
[![Last Update](https://img.shields.io/badge/Last%20Update-2026--05--28-ff006e.svg)](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/2026-05-28.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f5d4.svg)](LICENSE)

[中文版](README_CN.md) · [Live Archive →](https://jigexiansen.github.io/github-trending-archive/)

</div>

---

Open source moves fast. The tools everyone's talking about today might be forgotten by next month. This archive captures GitHub's daily trending page as standalone HTML reports — one per day, each with a unique visual style, stored here forever.

No databases. No APIs. Just a folder of HTML files that open in any browser, online or offline.

<div align="center">

**→ [Browse the Archive](https://jigexiansen.github.io/github-trending-archive/)**

</div>

---

## ✨ What's in each report

Each daily report is a single, self-contained HTML file:

| | |
|---|---|
| 🏆 **Top 10 repos** | Ranked by today's star count — momentum, not history |
| ⭐ **Star velocity bars** | Visual comparison of how fast each project is moving |
| 🗺️ **Language breakdown** | Weighted by today's activity, not repo count |
| 💡 **Trend insight** | A short written take on what the day's data actually means |
| 🎨 **Unique visual identity** | Editorial, dashboard, brutalist, minimal… no two reports look the same |
| 📦 **Zero dependencies** | Open it today, open it in 10 years — it just works |

---

## 📂 Browse

<details open>
<summary><strong>2026 · May</strong> — 3 reports</summary>

| Date | Top Project | Highlights | Visual Style |
|------|------------|-----------|--------------|
| [2026-05-28](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/2026-05-28.html) | Understand-Anything +4,465⭐ | 反 AI 套话浪潮 · Skills 生态持续爆发 | 全息终端仪表盘 |
| [2026-05-27](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/2026-05-27.html) | Understand-Anything +4,697⭐ | Skills 生态首次爆发 · Anthropic 插件官方入榜 | 赛博朋克仪表盘 |
| [2026-05-26](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/2026-05-26.html) | DeepSeek-TUI +5,787⭐ | AI Agent 基础设施生产化 · 终端原生工具崛起 | 深色社论风 |

</details>

---

## ⚙️ How reports are made

Every day, [Claude Code](https://claude.ai/code) scrapes `github.com/trending`, ranks the top 10 by today's stars, rewrites each description in Chinese, generates the visual report, and commits it here.

The data is real — nothing is fabricated or estimated. If something looks wrong, it was wrong on GitHub too (or it's a bug worth reporting).

```
Fetch → Rank → Describe → Visualize → Style → Archive
```

---

## 🚀 Run it locally

```bash
git clone https://github.com/jigexiansen/github-trending-archive
cd github-trending-archive

# Open any report directly
open reports/2026/05/2026-05-28.html
```

No setup. No install. Just open.

---

## 🤝 Contributing

Spotted a wrong star count? A broken link? A description that misses the mark?
→ Open a [data correction issue](../../issues/new?template=data-correction.md) — accuracy is the one thing we're strict about.

Have an idea for a visual style or feature?
→ Start a [discussion](../../discussions) — all ideas welcome.

---

## 📄 License

[MIT](LICENSE) — do whatever you want with this.

Data sourced from [github.com/trending](https://github.com/trending) · Generated with [Claude Code](https://claude.ai/code)
