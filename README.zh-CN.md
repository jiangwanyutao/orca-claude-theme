# Claude Theme for Orca

中文文档 · [English](README.md)

专为 [Orca](https://github.com/stablyai/orca) 打造的经典 **Claude Code** 风格主题插件。

<p align="center">
  <img src="images/cover.png" width="100%" alt="Claude Theme for Orca 预览图" />
</p>

---

## 主题特色

- 🏛️ **Claude Dark（暗色模式）**：深邃质感的暖炭黑底色（`#262624` / `#1A1A19`），搭配 Anthropic 标志性陶土红（`#D97757`），配合层次细腻的深色卡片与暖调对话气泡。
- 📜 **Claude Light（亮色模式）**：典雅的象牙暖白纸张底色（`#FAF9F5` / `#F0EEE6`），搭配温润高对比炭黑文字（`#302D29`）与深陶红强调色（`#A3442B`），阅读舒适且不刺眼。
- 💬 **针对 Orca AI 对话深度定制**：精心打磨了多智能体聊天界面的用户提问气泡、陶土色调行内代码药丸（Inline Code Pill）、纸张质感代码块及链接配色。
- 🔀 **Diff 与 Git 状态分层高亮**：兼顾行级背景（Background）与字符级强调（Emphasis）的温和绿/红对比色，长时间代码审查不易疲劳。
- 💻 **配套终端配色方案**：内置精心调校的 16 色 ANSI 终端主题，在集成终端中运行 Claude Code CLI、Codex 等智能体时，深浅文字均清晰可读。
- 🎨 **莫兰迪书卷语法高亮**：基于 TextMate 作用域细致调配的暖调莫兰迪高亮方案，保持专业、优雅与专注。
- 📁 **配套 Claude Icons 图标包（23 款图标）**：内置极简折纸风格文件夹与语言图标，全面覆盖 `.ts/.tsx`、`.js/.jsx`、`.py`、`.rs`、`.go`、`.json`、`.yaml/.yml`、`.toml`、`.env`、`Dockerfile`、`.sh/.ps1`、`.sql/.prisma`、`.lock`、`.md`、`.html`、`.css`、图片与 Git 配置文件。在 **Settings → Appearance → File Icon Theme** 中选择 **Claude Icons** 即可启用。
- ✨ **统一的全局悬停视觉层级**：精准对齐顶部导航项（入门清单/任务/工件）、工作区列表与文件树文件夹行的悬停光泽背景，主次分明。

---

## 核心色彩对照表

| 色彩令牌 | Claude Dark（暗色） | Claude Light（亮色） | 说明 |
| :--- | :--- | :--- | :--- |
| **强调色 (Primary)** | `#D97757` | `#A3442B` | 标志性陶土红 / 深陶红 |
| **画布底色 (Background)** | `#262624` | `#FAF9F5` | 暖炭黑 / 象牙暖白画布 |
| **编辑器表面 (Surface)** | `#1A1A19` | `#FFFFFF` | 代码编辑器与终端背景表面 |
| **主文本 (Foreground)** | `#ECE9E0` | `#302D29` | 主要文字墨色 |
| **次要文字 (Muted)** | `#B9B3A7` | `#625D55` | 次要描述与注解文本 |
| **侧边栏 (Sidebar)** | `#20201E` | `#F0EEE6` | 多工作区与文件树区域 |
| **统一悬停色 (Hover)** | `#2E2E2B` | `#E3E0D8` | 与 8% 前景透明度等效的悬停色 |
| **对话气泡 (Chat Bubble)**| `#33322E` | `#EDE8DE` | 用户提问消息气泡背景 |
| **行内代码 (Inline Code)**| `#EDA184` | `#91402B` | 聊天内行内代码药丸文字色 |
| **Diff 增添 (Added)** | `#A4BF88` | `#3D5F2C` | Git 差异插入标识色 |
| **Diff 删除 (Removed)** | `#E6A08B` | `#9E3B32` | Git 差异删除标识色 |

---

## 安装方法

### 通过 Orca 插件市场安装
在 Orca 官方插件市场索引后，在 **Settings → Plugins** 中搜索 **Claude Theme**，点击 **Install** 即可。

### 本地路径安装（开发与调试）
1. 克隆或下载本仓库。
2. 打开 **Orca** 桌面客户端。
3. 进入 **Settings**（快捷键 `Ctrl + ,` 或 macOS 上的 `Cmd + ,`）→ **Plugins**。
4. 点击 **"Install from local path"**（从本地路径安装），选择本仓库文件夹。
5. 进入 **Settings → Appearance**（外观），在主题下拉菜单中选择 **Claude Dark** 或 **Claude Light**，并在文件图标主题中选择 **Claude Icons**。

### 通过 Orca CLI 加载
```bash
orca plugin dev load /path/to/orca-claude-theme
```

---

## 开源协议

[MIT](LICENSE)
