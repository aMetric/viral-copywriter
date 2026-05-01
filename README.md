<p align="center">
  <img src="https://img.shields.io/badge/状态-已发布-brightgreen?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/许可-MIT-blue?style=flat-square" alt="License">
  <img src="https://img.shields.io/badge/平台-Web%20%7C%20Mac%20%7C%20Windows-lightgrey?style=flat-square" alt="Platform">
</p>

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI Compatible">
</div>

<br>

<div align="center">
  <h1>✦ 爆款文案工坊 · ViralCopy</h1>
  <p><strong>AI 驱动的社交媒体爆款文案生成工具</strong></p>
  <p>支持小红书 · 抖音 · 多平台通用 · 20+ 专业模板 · 一键生成</p>
  <br>
  <p>
    <a href="#-功能特性">功能特性</a> •
    <a href="#-在线预览">在线预览</a> •
    <a href="#-快速开始">快速开始</a> •
    <a href="#-配置说明">配置说明</a> •
    <a href="#-使用指南">使用指南</a> •
    <a href="#-部署到服务器">部署到服务器</a> •
    <a href="#-常见问题">常见问题</a>
  </p>
</div>

---

## 📖 项目简介

**爆款文案工坊** 是一个纯前端、无需后端的 AI 文案生成工具。它通过调用 OpenAI 兼容接口（支持 GPT、DeepSeek、Claude 等任意模型），帮助自媒体创作者、运营人员快速生成高质量的小红书种草文案、抖音带货脚本、爆款标题等内容。

项目最初受启发于国内主流社交媒体平台的内容创作需求。所有代码都在一个 HTML 文件中，**无需安装任何依赖**，双击即可运行。

---

## ✨ 功能特性

### 🎯 三大平台
| 平台 | 模板数量 | 适用场景 |
|------|---------|---------|
| 📕 **小红书** | 8 个专业模板 | 种草文案、干货分享、情感故事、Vlog、美妆穿搭、探店打卡、避坑指南、合集整理 |
| 🎵 **抖音** | 8 个爆款模板 | 搞笑段子、知识科普、情感语录、产品带货、生活技巧、热门挑战、剧情反转、街访问答 |
| 🌐 **多平台通用** | 4 个实用模板 | 爆款标题、蹭热点文案、神回复评论、短视频脚本 |

### 🎨 玩法丰富
- **6 种语气调节**：轻松活泼 / 专业严谨 / 幽默风趣 / 感性走心 / 热情激昂
- **4 级 Emoji 控制**：从无到多，自由调配
- **4 档字数范围**：短 (50-150字) / 中 (150-350字) / 长 (350-600字) / 超长 (600-1000字)
- **批量生成**：一次可生成 1/2/3/5 份不同版本
- **目标受众 & 关键词**：精准定位读者群体
- **热度预测评分**：每条文案自动生成爆款潜力评分（🔥/💪/👍/📝）
- **单条重写**：对不满意的结果单独重新生成
- **收藏 & 复制**：一键收藏喜欢的文案，一键复制到剪贴板
- **历史记录**：侧边栏保存最多 100 条历史记录，可随时恢复

### 🎨 视觉体验
- **🌗 深色/浅色主题**：一键切换，保护眼睛
- **毛玻璃设计**：现代感十足的玻璃态卡片
- **动效反馈**：加载动画、结果滑入、热度条渐变
- **响应式布局**：桌面 / 平板 / 手机 完美适配

---

## 🚀 快速开始

### 环境要求

> ✅ **零依赖**：本项目的核心就是一个 HTML 文件，无需任何编程环境！
> 
> 你只需要：
> - 一个现代浏览器（Chrome / Edge / Safari / Firefox）
> - 一个 **OpenAI 兼容的 API Key**（GPT、DeepSeek、Kimi、Claude 等都可以）

---

### 方法一：直接打开（最简单）

这是最快速的方式，适合**只是想试用**的用户。

**Mac 用户：**
```
1. 下载 index.html 文件到电脑上
2. 双击 index.html 文件（会自动用浏览器打开）
3. 开始使用！
```

**Windows 用户：**
```
1. 下载 index.html 文件到电脑上
2. 双击 index.html 文件（会自动用默认浏览器打开）
3. 开始使用！
```

> ⚠️ **注意**：直接双击打开时，某些浏览器可能会限制跨域请求。如果遇到 API 调用失败，请使用方法二。

---

### 方法二：使用 Python 启动本地服务器（推荐）

这个方法更加稳定，推荐大多数用户使用。需要电脑上已经安装 Python（Mac 自带，Windows 需安装）。

#### 📦 检查 Python 是否已安装

**Mac 用户：**
打开「终端」应用（在「启动台」-「其他」中，或按 `Command + 空格` 搜索"终端"），输入：
```bash
python3 --version
```
如果显示 `Python 3.x`，说明已安装。

**Windows 用户：**
打开「命令提示符」（按 `Win + R`，输入 `cmd` 并回车），输入：
```bash
python --version
```
如果显示 `Python 3.x`，说明已安装。

> 如果未安装 Python，请访问 https://www.python.org/downloads/ 下载安装
> 安装时记得勾选 **"Add Python to PATH"**（Windows 用户特别注意）

#### 🚀 启动项目

**Mac 用户：**
```bash
# 1. 打开终端，进入项目文件夹
cd path/to/viral-copywriter

# 2. 启动 HTTP 服务器（两种方式任选其一）
python3 -m http.server 5173

# 或使用 Node.js（如果你安装了 Node）
npx serve . -l 5173
```

**Windows 用户：**
```bash
# 1. 打开命令提示符或 PowerShell，进入项目文件夹
cd path\to\viral-copywriter

# 2. 启动 HTTP 服务器（两种方式任选其一）
python -m http.server 5173

# 或使用 Node.js（如果你安装了 Node）
npx serve . -l 5173
```

#### 🌐 打开项目

启动服务器后，打开浏览器访问：
```
http://localhost:5173
```

你会看到项目运行界面。如果端口 5173 被占用，可以改成其他数字（如 8080）。

---

### 方法三：使用 Node.js（适合前端开发者）

如果你安装了 Node.js，可以直接使用项目自带的命令：

```bash
# 1. 进入项目目录
cd path/to/viral-copywriter

# 2. 启动（将自动使用 npx serve 启动服务器）
npm start
```

然后打开浏览器访问 `http://localhost:5173`。

---

## ⚙️ 配置说明

### 获取 API Key

项目需要调用 AI 模型的 API 接口。如果你还没有 API Key，可以从以下服务商获取：

| 服务商 | 官方地址 | 说明 |
|-------|---------|------|
| **OpenAI** | https://platform.openai.com/api-keys | GPT-4o / GPT-4 / GPT-3.5 |
| **DeepSeek** | https://platform.deepseek.com | 国产模型，性价比高 |
| **Moonshot（月之暗面）** | https://platform.moonshot.cn | Kimi 模型 |
| **智谱 AI** | https://open.bigmodel.cn | GLM 系列模型 |
| **阿里千问** | https://help.aliyun.com/zh/model-studio | Qwen 系列模型 |

### 配置步骤

1. 打开项目页面
2. 点击右上角的 **⚙️ API 配置** 按钮
3. 在弹出的面板中填写：

| 字段 | 说明 | 示例 |
|-----|------|------|
| **API Key** | 你的 API 密钥 | `sk-xxxxxxxxxxxx` |
| **Base URL** | API 的请求地址（注意不要漏掉 `/v1`） | `https://api.openai.com/v1` |
| **模型** | 要使用的模型名称 | `gpt-4o` / `deepseek-chat` |

4. 点击 **💾 保存配置**（配置会自动保存在浏览器中，下次打开不用重新填写）

> 💡 **常见 API Base URL 参考**
> - OpenAI: `https://api.openai.com/v1`
> - DeepSeek: `https://api.deepseek.com`
> - 月之暗面 (Kimi): `https://api.moonshot.cn/v1`
> - 智谱 GLM: `https://open.bigmodel.cn/api/paas/v4`
> - 阿里千问: `https://dashscope.aliyuncs.com/compatible-mode/v1`

---

## 📝 使用指南

### 第一步：生成文案

1. **选择平台**：点击顶部「📕小红书」「🎵抖音」或「🌐多平台通用」
2. **选择模板**：点击喜欢的爆款模板（如"好物推荐种草"）
3. **补充需求（可选）**：在文本框中填写你的具体需求
4. **调节参数**：选择合适的语气、Emoji 程度、字数等
5. **点击生成**：点击「✨ 生成爆款文案」按钮
6. **等待结果**：系统会依次生成多份文案，并展示热度评分

### 第二步：处理结果

每条生成的结果都支持以下操作：

| 操作 | 说明 |
|-----|------|
| ❤️ **收藏** | 收藏好的文案，方便以后查找 |
| 📋 **复制** | 一键复制文案到剪贴板 |
| 🔄 **重写** | 对不满意的那条单独重新生成 |
| 🔥 **热度预测** | 自动评分（爆款潜力 / 优质内容 / 中规中矩 / 需要优化） |

### 第三步：管理历史

- 点击右上角 **📜 历史记录** 按钮查看过往生成的内容
- 点击任意历史记录可恢复文案
- 支持单个删除或一键清空

### 切换主题

- 点击右上角的 🌙/☀️ 按钮，可在**深色模式**和**浅色模式**之间切换
- 主题偏好会自动保存，下次打开页面自动恢复

---

## 🚢 部署到服务器

### 部署到 Vercel（推荐，免费）

[Vercel](https://vercel.com) 是一个免费的静态网站托管平台。

```bash
# 1. 安装 Vercel CLI（如果没有）
npm install -g vercel

# 2. 在项目目录执行部署
vercel --prod
```

> 也可以直接将 GitHub 仓库导入 Vercel，会自动部署。

### 部署到 GitHub Pages（免费）

1. 在 GitHub 上创建仓库，将项目文件推送到仓库
2. 进入仓库 Settings → Pages
3. Source 选择 "Deploy from a branch"
4. Branch 选择 `main`，目录选择 `/ (root)`
5. 点击 Save，等待几分钟即可访问
6. 访问地址：`https://<你的用户名>.github.io/<仓库名>/`

### 部署到 Nginx / Apache

将整个项目文件夹上传到服务器的网站根目录即可，纯静态文件无需额外配置。

### 部署到腾讯云 / 阿里云 OSS

1. 将 `index.html` 和其他文件上传到 OSS 存储桶
2. 开启静态网站托管功能
3. 获取分配的访问域名

---

## 🗂️ 项目结构

```
viral-copywriter/
├── index.html          # 🎯 主应用（单页，包含全部 HTML/CSS/JS）
├── package.json        # 📦 Node.js 快捷启动脚本（可选）
├── .gitignore          # 🙈 Git 忽略规则
└── README.md           # 📖 本说明文档
```

> 整个项目只有一个核心文件 `index.html`，真正的"零部署"！

---

## ❓ 常见问题

### Q: 为什么我双击 `index.html` 打开后 API 调用报错？

这是由于浏览器的安全策略（CORS 跨域限制）。请使用 Python 或 Node.js 启动 HTTP 服务器（参考"方法二"）。

### Q: 我的 API Key 安全吗？

**完全安全。** API Key 仅保存在你电脑浏览器的 `localStorage` 中，不会上传到任何第三方服务器，也不会通过代码发送到其他地方。每次调用 API 时直接从浏览器发送请求到 AI 服务商，不经由任何中转服务器。

### Q: 支持哪些 AI 模型？

任何兼容 OpenAI API 格式的模型都支持，包括但不限于：
- GPT-4o / GPT-4 / GPT-3.5-turbo
- DeepSeek-V3 / DeepSeek-R1
- Claude (通过 Anthropic API 的 OpenAI 兼容模式)
- 月之暗面 Kimi
- 智谱 GLM-4
- 阿里通义千问 Qwen

### Q: 生成文案的质量如何？

文案质量取决于你使用的 AI 模型和提示词的详细程度。建议：
- 使用 GPT-4o / DeepSeek 等较强模型效果最佳
- 选择匹配的模板，并尽量补充具体的产品/主题信息
- 如果第一次效果不理想，可以点击「🔄 重写」重新生成

### Q: 页面打开是英文的，但我想要中文？

本项目界面默认就是中文。如果浏览器显示异常，请检查浏览器语言设置是否优先使用中文。

### Q: 历史记录存在哪里？会丢失吗？

历史记录保存在你浏览器的 `localStorage` 中。**清理浏览器缓存/数据会丢失历史记录**，建议重要的文案及时复制保存到其他地方。

### Q: 如何重置所有设置？

打开浏览器开发者工具（F12），在 Console 中执行：
```javascript
localStorage.clear();
```
然后刷新页面即可重置所有配置和历史记录。

### Q: 手机/平板上能使用吗？

**可以。** 项目完全响应式设计，在手机和平板上会自动适配布局。但生成文案时 API 调用仍然需要网络连接。

---

## 🧑‍💻 开发者信息

### 技术栈
- **纯前端**：HTML5 + CSS3 + JavaScript (ES6+)
- **无框架**：零依赖，不依赖任何前端框架或库
- **API 协议**：OpenAI Chat Completions API 兼容格式
- **存储**：浏览器 localStorage
- **字体**：Sora + DM Sans（Google Fonts）
- **设计**：深色/浅色双主题 · 毛玻璃效果 · 响应式布局

### 兼容性
- Chrome 90+ ✅
- Edge 90+ ✅
- Safari 15+ ✅
- Firefox 90+ ✅
- 移动端浏览器 ✅

### 本地开发

由于项目是纯静态单页应用，任何代码修改后只需刷新浏览器即可看到效果。

---

## 📄 许可证

本项目基于 MIT 许可证开源，你可以自由地使用、修改、分发。

---

<div align="center">
  <p>如果这个项目对你有帮助，欢迎 ⭐ Star 支持！</p>
  <p>Made with ❤️ for content creators</p>
</div>
