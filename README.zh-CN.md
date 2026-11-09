# Claude Theme for Orca

中文文档 · [English](README.md)

专为 [Orca](https://github.com/stablyai/orca) 打造的经典 **Claude Code** 风格主题插件。

<p align="center">
  <img src="images/cover.png" width="100%" alt="Claude Theme for Orca 预览图" />
</p>

---

## 主题特色

- 🏛️ **4 种书卷质感主题变体**：
  - **Claude Dark（经典暖炭黑）**：Anthropic 标志性暖炭黑画布（`#262624` / `#1A1A19`），经典陶土红强调色（`#D97757`）。
  - **Claude Dark (Midnight OLED 午夜极黑)**：深邃纯黑画布（`#141413` / `#0C0C0B`），高对比陶土红荧光质感，OLED 屏幕更加省电。
  - **Claude Light（经典象牙暖白）**：温润如纸的象牙暖白底色（`#FAF9F5` / `#F0EEE6`），高对比炭黑文字（`#302D29`）与深陶红（`#A3442B`）。
  - **Claude Light (Pure White 纯白高光)**：清透利落的纯白底色（`#FFFFFF` / `#F7F6F2`），适合强光环境或偏好极高明暗反差的使用者。
- 💬 **Orca AI 对话全套视觉适配（100% 覆盖 · 73/73 个完整令牌）**：深度定制了用户提问气泡、粗体加重、时间戳弱化、陶土色行内代码药丸、纸张质感代码块与聊天专属选区高亮。
- 🔀 **Diff 与 Git 状态分层高亮**：兼顾行级背景（Background）与字符级强调（Emphasis）的温和绿/红对比色，长时间代码审查不易疲劳。
- 💻 **4 套独立终端主题预设**：配套调校的 16 色 ANSI 终端主题，支持经典陶土红光标、高对比墨黑光标及深空纯黑终端，在集成终端中运行 Claude Code CLI、Codex 等智能体色彩浑然天成。
- 📁 **语义化文件夹与 29 款文件图标**：针对 `src/`、`components/`、`docs/`、`test/`、`dist/`、`public/`、`config/`、`.git/` 与 `node_modules/` 配备专属闭合/展开折纸图标，外加 29 款语言/文件扩展名图标。
- 🎨 **莫兰迪书卷语法高亮**：基于 TextMate 作用域细致调配的暖调莫兰迪高亮方案，包含参数（Parameters）、装饰器（Decorators）与正则表达式（Regexp）专属着色。
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

## 推荐 Claude 字体与光标配置

为了在 Orca 中获得最正宗的 Anthropic Claude Desktop 质感：

1. **终端 2px 纤细竖线光标**：
   - 打开 **Settings (`Ctrl + ,`) → Terminal**。
   - 将 **`Cursor Style`** 从 `block`（方块）改为 **`bar`**（竖线），并建议开启 `Cursor Blink`。
2. **代码编辑器字体**：
   - **Settings → Editor → Font Family** 建议填入：`'JetBrains Mono', 'SF Mono', 'Fira Code', Consolas, monospace`。
   - **Line Height** 设置为 **`1.6`**，达到黄金阅读节奏。

---

## 安装方法

### 通过 Orca 插件市场安装
在 Orca 官方插件市场索引后，在 **Settings → Plugins** 中搜索 **Claude Theme**，点击 **Install** 即可。

### 本地路径安装（开发与调试）
1. 克隆或下载本仓库。
2. 打开 **Orca** 桌面客户端。
3. 进入 **Settings**（快捷键 `Ctrl + ,` 或 macOS 上的 `Cmd + ,`）→ **Plugins**。
4. 点击 **"Install from local path"**（从本地路径安装），选择本仓库文件夹。
5. 进入 **Settings → Appearance**（外观），在主题下拉菜单中挑选喜欢的 Claude 主题变体，并在文件图标主题中选择 **Claude Icons**。

### 通过 Orca CLI 加载
```bash
orca plugin dev load /path/to/orca-claude-theme
```

---

## 开源协议

[MIT](LICENSE)
