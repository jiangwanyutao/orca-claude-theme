# Claude Theme for Orca

[中文文档](README.zh-CN.md) · English

An authentic **Claude Code** aesthetic theme for [Orca](https://github.com/stablyai/orca).

<p align="center">
  <img src="images/cover.png" width="100%" alt="Claude Theme for Orca Preview" />
</p>

---

## Features

- 🏛️ **Claude Dark**: Deep warm charcoal canvas (`#262624` / `#1A1A19`), Anthropic terracotta accent (`#D97757`), layered surfaces, and warm message bubble styling.
- 📜 **Claude Light**: Signature ivory/warm paper canvas (`#FAF9F5` / `#F0EEE6`), readable charcoal ink (`#302D29`), and deep clay terracotta accents (`#A3442B`).
- 💬 **Full Orca Chat AI Suite**: 100% token coverage (73/73 tokens) including user bubbles, bold emphasis, muted timestamps, terracotta code pills, paper code blocks, and custom chat text selection.
- 🔀 **Diff & Git Highlighting**: Balanced line-level backgrounds and crisp character-level emphasis for fatigue-free code reviews.
- 💻 **Claude Terminal Themes**: Matching 16-color ANSI terminal palettes tuned for CLI coding agents (Claude Code CLI, Codex, etc.).
- 🎨 **Editorial Syntax Colors**: Refined Morandi TextMate token color scheme providing warm, distraction-free syntax highlighting with dedicated scopes for parameters, decorators, and regular expressions.
- 📁 **Bundled Claude Icons (29 Icons)**: Minimalist folded-paper folder and language icons covering `.ts/.tsx`, `.js/.jsx`, `.vue`, `.svelte`, `.c/.cpp`, `.java`, `.py`, `.rs`, `.go`, `.json`, `.yaml/.yml`, `.toml`, `.graphql`, `.env`, `Dockerfile`, `.sh/.ps1`, `.sql/.prisma`, `.lock`, `.zip/.tar`, `.md`, `.html`, `.css`, `.svg/.png`, and Git files. Activate under **Settings → Appearance → File Icon Theme → Claude Icons**.
- ✨ **Unified Hover Hierarchy**: Cohesive, subtle hover highlights across top navigation items, worktrees, and file tree folders.

---

## Color Palette

| Token | Claude Dark | Claude Light | Description |
| :--- | :--- | :--- | :--- |
| **Accent (Primary)** | `#D97757` | `#A3442B` | Signature Terracotta / Deep Clay |
| **Canvas (Background)**| `#262624` | `#FAF9F5` | Warm Charcoal / Ivory Canvas |
| **Editor Surface** | `#1A1A19` | `#FFFFFF` | Code Editor & Terminal Surface |
| **Foreground** | `#ECE9E0` | `#302D29` | Primary Text Ink |
| **Muted Ink** | `#B9B3A7` | `#625D55` | Secondary & Subtitle Text |
| **Sidebar** | `#20201E` | `#F0EEE6` | Navigation & Worktree Tree |
| **Hover Accent** | `#2E2E2B` | `#E3E0D8` | Unified 8% Equivalent Hover Fill |
| **Chat Bubble** | `#33322E` | `#EDE8DE` | User Message Bubble Fill |
| **Inline Code Text** | `#EDA184` | `#91402B` | Backtick Code Pill Foreground |
| **Diff Added** | `#A4BF88` | `#3D5F2C` | Git Insertion Indicator |
| **Diff Removed** | `#E6A08B` | `#9E3B32` | Git Deletion Indicator |

---

## Installation

### From Orca Plugin Marketplace
Once indexed, search for **Claude Theme** under **Settings → Plugins** and click **Install**.

### From Local Path (For Development)
1. Clone or download this repository.
2. Open **Orca Desktop**.
3. Navigate to **Settings** (`Ctrl + ,` on Windows/Linux or `Cmd + ,` on macOS) → **Plugins**.
4. Click **"Install from local path"** and select this directory.
5. In **Settings → Appearance**, choose **Claude Dark** or **Claude Light**, and set **File Icon Theme** to **Claude Icons**.

### Via Orca CLI
```bash
orca plugin dev load /path/to/orca-claude-theme
```

---

## License

[MIT](LICENSE)
