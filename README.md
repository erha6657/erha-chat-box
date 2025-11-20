# Erha Chat Pro (Erha的简易聊天工具) 🤖

这是一个基于 **Vibe Coding (AI-Assisted Development)** 模式开发的单文件 HTML 聊天应用。它无需任何后端环境（如 Node.js/Python），直接在浏览器运行，支持对接 OpenAI 格式的第三方 API（如 DeepSeek, Qwen, Gemini 等）。

## ✨ 功能亮点 (Features)
- **零依赖部署**：单文件 HTML，双击即用，基于 CDN 引入 Tailwind CSS 和 Marked.js。
- **多模型兼容**：完美适配 OpenAI 接口格式，支持 DeepSeek、通义千问等。
- **数据隐私**：所有聊天记录和 API Key 仅存储在浏览器本地 (LocalStorage)，不经过任何中间服务器。
- **专业级交互**：
  - 支持流式传输 (Stream) 打字机效果。
  - 支持 Markdown 渲染与代码高亮。
  - 支持会话管理、历史记录保存。
  - **编辑与重Roll**：可修改历史消息，可重新生成 AI 回复。
- **配置管理**：支持保存多个 API 站点预设，一键切换。

## 🚀 如何使用 (How to use)
1. 下载本项目中的 `index.html`。
2. 双击在浏览器打开。
3. 在设置面板输入 API 地址和 Key (例如 DeepSeek 或中转站)。
4. 开始聊天！(Ctrl + Enter 发送)

## 🛠️ 开发过程 (Vibe Coding Journey)
本项目完全通过自然语言交互开发。我通过不断的 Prompt 迭代，引导 AI 完成了从原型到成品的构建。
- **Tech Stack**: HTML5, Vanilla JavaScript, Tailwind CSS.
- **Key Challenges Solved**: 解决跨域问题、适配不同厂商的 API 格式、实现复杂的会话状态管理。

---
*Created by Erha via Vibe Coding.*
