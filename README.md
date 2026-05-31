<div align="center">

# 📡 GitHub Trending Archive

**A permanent, beautiful record of what the open source world cared about each day.**

[![Validate Reports](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml/badge.svg)](https://github.com/jigexiansen/github-trending-archive/actions/workflows/validate.yml)
[![Reports](https://img.shields.io/badge/Reports-6-7b2fff.svg)](#-browse)
[![Last Update](https://img.shields.io/badge/Last%20Update-2026--05--31-ff006e.svg)](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/31.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-00f5d4.svg)](LICENSE)

[简体中文](README_zh-CN.md) · [Live Archive →](https://jigexiansen.github.io/github-trending-archive/)

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
| 🎨 **Distinct visual design** | Every report has its own look — no two days feel the same |
| 📦 **Zero dependencies** | Open it today, open it in 10 years — it just works |

---

## 📂 Browse

<details open>
<summary><strong>2026 · May</strong> — 5 reports</summary>

| Date | Top Project | Highlights |
|------|------------|-----------|
| [2026-05-31](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/31.html) | MoneyPrinterTurbo +2,768⭐ | AI toolchain focuses on video & docs · Python takes 65% of stars · Rust rises in system AI |
| [2026-05-30](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/30.html) | MoneyPrinterTurbo +3,567⭐ | AI efficiency tools surge · anti-slop wave continues · Python dominates |
| [2026-05-29](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/29.html) | MoneyPrinterTurbo +4,698⭐ | AI toolchains erupt across layers · anti-slop wave continues · skills framework ecosystem expands |
| [2026-05-28](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/28.html) | Understand-Anything +4,465⭐ | Anti-slop wave continues · Skills ecosystem keeps surging |
| [2026-05-27](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/27.html) | Understand-Anything +4,697⭐ | Skills ecosystem's first surge · Anthropic plugins hit the official board |
| [2026-05-26](https://jigexiansen.github.io/github-trending-archive/reports/2026/05/26.html) | DeepSeek-TUI +5,787⭐ | AI Agent infrastructure goes production · terminal-native tools rise |

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
