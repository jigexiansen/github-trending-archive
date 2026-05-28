<div align="center">

# 📡 GitHub Trending Archive

**Daily snapshots of GitHub's trending repositories — beautifully visualized, permanently archived.**

[![License: MIT](https://img.shields.io/badge/License-MIT-00f5d4.svg)](LICENSE)
[![Reports](https://img.shields.io/badge/Reports-1-7b2fff.svg)](#-browse-reports)
[![Last Update](https://img.shields.io/badge/Last%20Update-2026--05--28-ff006e.svg)](reports/2026/05/2026-05-28.html)
[![Data Source](https://img.shields.io/badge/Source-GitHub%20Trending-181717?logo=github)](https://github.com/trending)

</div>

---

Each day, the top 10 trending GitHub repositories are captured and rendered as a **self-contained, visually distinct HTML report** — no build step, no dependencies, no servers. Just open and read.

Every report ships with a unique visual aesthetic (editorial, dashboard, brutalist, minimal…), today-star bar charts, a language distribution breakdown, and a hand-crafted Chinese trend insight summary.

<div align="center">

**→ [View Latest Report · 2026-05-28](reports/2026/05/2026-05-28.html)**

</div>

---

## ✨ What's Inside Each Report

| Feature | Detail |
|---|---|
| 🏆 **Top 10 Repos** | Ranked by today's star count, not total stars |
| ⭐ **Star Bars** | Animated visual comparison of today's momentum |
| 🗺️ **Language Chart** | Distribution weighted by today's stars |
| 💡 **Trend Insight** | 2–3 sentence analysis of the day's theme (Chinese) |
| 🎨 **Unique Visual Style** | New aesthetic each day — no two reports look alike |
| 📦 **Self-Contained** | Single `.html` file, zero dependencies, works offline |

---

## 📂 Browse Reports

```
reports/
└── 2026/
    └── 05/
        └── 2026-05-28.html  ← Today
```

### 2026

<details open>
<summary><strong>May 2026</strong></summary>

| Date | Highlights | Style |
|------|-----------|-------|
| [2026-05-28](reports/2026/05/2026-05-28.html) | Understand-Anything +4,465⭐ · 反 AI 套话浪潮 | 全息终端仪表盘 |

</details>

---

## 🗂️ Repository Structure

```
github-trending-archive/
├── reports/                  # All archived reports
│   └── YYYY/
│       └── MM/
│           └── YYYY-MM-DD.html
├── README.md
├── LICENSE
└── .gitignore
```

**Naming convention:** `reports/YYYY/MM/YYYY-MM-DD.html`  
Each file is a fully standalone HTML document — clone the repo and open any file directly in your browser.

---

## 🚀 Usage

**Clone and browse locally:**
```bash
git clone https://github.com/jigexiansen/github-trending-archive
cd github-trending-archive

# Open the latest report
open reports/2026/05/2026-05-28.html

# Or browse all reports
ls reports/2026/
```

**Browse on GitHub:**  
Navigate the [`reports/`](reports/) directory tree and click any `.html` file → use the **Raw** button → open in your browser.

---

## ⚙️ How It's Generated

Reports are generated daily using [Claude Code](https://claude.ai/code) with the `/trending-sync` skill:

1. **Fetch** — Scrapes `github.com/trending` for the day's top 10
2. **Rank** — Sorts by today's star count (not total stars)
3. **Describe** — Rewrites each project description in idiomatic Chinese
4. **Visualize** — Generates animated star bars + language distribution chart
5. **Style** — Applies a unique visual aesthetic per report (never repeated)
6. **Archive** — Saves locally and pushes to this repository

All data comes directly from GitHub Trending. No data is fabricated or interpolated.

---

## 📊 Stats

| Metric | Value |
|--------|-------|
| Total reports | 1 |
| Date range | 2026-05-28 → present |
| Languages tracked | Python, TypeScript, JavaScript, Shell, Go, Rust, and more |
| Update frequency | Daily |

---

## 🤝 Contributing

Found a bug in a report? Want to improve the generation skill?

- **Report issues** via [GitHub Issues](../../issues)
- **Discuss trends** via [GitHub Discussions](../../discussions)

Data corrections for existing reports are welcome as PRs — include the date and the corrected field.

---

## 📄 License

[MIT](LICENSE) © 2026 jigexiansen

Data sourced from [github.com/trending](https://github.com/trending) — GitHub's public trending page.

---

<div align="center">

Made with [Claude Code](https://claude.ai/code) · Updated daily · [↑ Back to top](#-github-trending-archive)

</div>
