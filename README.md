# Claude Theme for Orca

[中文文档](README.zh-CN.md) · English

An authentic **Claude Code** aesthetic theme for [Orca](https://github.com/stablyai/orca).

<p align="center">
  <img src="images/icon.png" width="128" height="128" alt="Claude Theme Icon" />
</p>

---

## Features

- 🏛️ **Claude Dark**: Deep warm charcoal canvas (`#191919`), Anthropic terracotta accent (`#d97757`), layered surfaces, and warm message bubble styling.
- 📜 **Claude Light**: Signature ivory/warm paper canvas (`#faf9f5`), readable charcoal ink (`#161616`), and elegant terracotta accents.
- 💬 **Orca AI Chat Tailored**: Specifically styled user message bubbles, inline code pills, and highlighted code blocks designed for Orca's multi-agent workflow.
- 🔀 **Diff & Git Highlighting**: High-contrast, fatigue-free green and red diff indicators for code review.
- 💻 **Claude Terminal Themes**: Matching 16-color ANSI terminal palettes for integrated agent runs (Claude Code CLI, Codex, etc.).
- 🎨 **Editorial Syntax Colors**: Refined TextMate token color scheme providing balanced, distraction-free syntax highlighting.
- 📁 **Bundled Claude Icons**: Minimalist folded-paper folder and language icons. Activate under **Settings → Appearance → File Icon Theme → Claude Icons**.
- ✨ **Subtle Hover Indicators**: Gentle, translucent hover highlights on sidebar items and folders that guide the eye without competing with active selections.

---

## Color Palette

| Token | Claude Dark | Claude Light | Description |
| :--- | :--- | :--- | :--- |
| **Accent (Primary)** | `#d97757` | `#d97757` | Signature Terracotta Clay |
| **Canvas (Background)**| `#191919` | `#faf9f5` | Warm Charcoal / Ivory Canvas |
| **Surface (Card)** | `#232323` | `#ffffff` | Elevated Surfaces & Cards |
| **Foreground** | `#fdfdfd` | `#161616` | Primary Text Ink |
| **Muted Ink** | `#9c9395` | `#70686a` | Secondary & Subtitle Text |
| **Sidebar** | `#1f1f1f` | `#f3f1ea` | Navigation & Worktree Tree |
| **Chat Bubble** | `#282524` | `#f4f2f3` | User Message Bubble Fill |
| **Diff Added** | `#569e6b` | `#3d7550` | Git Insertion Indicator |
| **Diff Removed** | `#d96666` | `#c94f4f` | Git Deletion Indicator |

---

## Installation

### From Orca Plugin Marketplace
Once indexed, search for **Claude Theme** under **Settings → Plugins** and click **Install**.

### From Local Path (For Development)
1. Clone or download this repository.
2. Open **Orca Desktop**.
3. Navigate to **Settings** (`Ctrl + ,` on Windows/Linux or `Cmd + ,` on macOS) → **Plugins**.
4. Click **"Install from local path"** and select this directory.
5. In **Settings → Appearance**, choose **Claude Dark** or **Claude Light**.

### Via Orca CLI
```bash
orca plugin dev load /path/to/orca-claude-theme
```

---

## License

[MIT](LICENSE)
