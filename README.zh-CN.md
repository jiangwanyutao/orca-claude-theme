# Claude Theme for Orca

中文文档 · [English](README.md)

专为 [Orca](https://github.com/stablyai/orca) 打造的经典 **Claude Code** 风格主题插件。

<p align="center">
  <img src="images/icon.png" width="128" height="128" alt="Claude Theme Icon" />
</p>

---

## 主题特色

- 🏛️ **Claude Dark（暗色模式）**：深邃质感的暖炭黑底色（`#191919`），搭配 Anthropic 标志性陶土红（`#d97757`），配合层次细腻的深色卡片与暖调对话气泡。
- 📜 **Claude Light（亮色模式）**：典雅的象牙暖白纸张底色（`#faf9f5`），搭配温润高对比炭黑文字（`#161616`），阅读舒适且不刺眼。
- 💬 **针对 Orca AI 对话定制**：精心适配了多智能体聊天界面的用户提问气泡、行内代码药丸、代码块及链接配色。
- 🔀 **Diff 与 Git 状态高亮**：温和且高辨识度的绿/红代码差异对比色，长时间进行代码审查不易疲劳。
- 💻 **配套终端配色方案**：内置配套的 16 色 ANSI 终端主题，无论在集成终端中运行 Claude Code CLI、Codex 还是其他 Agent，色彩均与界面浑然一体。
- 🎨 **书卷气息语法高亮**：基于 TextMate 作用域细致调配的代码高亮方案，保持专业、优雅与专注。

---

## 核心色彩对照表

| 色彩令牌 | Claude Dark（暗色） | Claude Light（亮色） | 说明 |
| :--- | :--- | :--- | :--- |
| **强调色 (Primary)** | `#d97757` | `#d97757` | 标志性陶土红 (Terracotta Clay) |
| **画布底色 (Background)** | `#191919` | `#faf9f5` | 暖炭黑 / 象牙暖白画布 |
| **卡片与表面 (Card)** | `#232323` | `#ffffff` | 浮层与容器表面色 |
| **主文本 (Foreground)** | `#fdfdfd` | `#161616` | 主要文字墨色 |
| **次要文字 (Muted)** | `#9c9395` | `#70686a` | 次要描述与注解文本 |
| **侧边栏 (Sidebar)** | `#1f1f1f` | `#f3f1ea` | 多工作区与文件树区域 |
| **对话气泡 (Chat Bubble)**| `#282524` | `#f4f2f3` | 用户提问消息气泡背景 |
| **Diff 增添 (Added)** | `#569e6b` | `#3d7550` | Git 差异插入标识色 |
| **Diff 删除 (Removed)** | `#d96666` | `#c94f4f` | Git 差异删除标识色 |

---

## 安装方法

### 通过 Orca 插件市场安装
在 Orca 官方插件市场索引后，在 **Settings → Plugins** 中搜索 **Claude Theme**，点击 **Install** 即可。

### 本地路径安装（开发与调试）
1. 克隆或下载本仓库。
2. 打开 **Orca** 桌面客户端。
3. 进入 **Settings**（快捷键 `Ctrl + ,` 或 macOS 上的 `Cmd + ,`）→ **Plugins**。
4. 点击 **"Install from local path"**（从本地路径安装），选择本仓库文件夹。
5. 进入 **Settings → Appearance**（外观），在主题下拉菜单中选择 **Claude Dark** 或 **Claude Light**。

### 通过 Orca CLI 加载
```bash
orca plugin dev load /path/to/orca-claude-theme
```

---

## 开源协议

[MIT](LICENSE)
