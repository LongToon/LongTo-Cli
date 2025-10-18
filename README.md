<img width="935" height="317" alt="1760796620327" src="https://github.com/user-attachments/assets/9fe218c5-b285-4601-8350-5703e4773c13" />
LongTo CLI 是一个开源的 AI 助手，专为开发者和中文用户打造。从Gemini CLI改进而来，它直接在您的终端中提供强大的多模型 AI 能力，包括 GLM、Qwen 和其他主流模型，为您提供最直接的 AI 辅助开发体验。

## 🚀 为什么选择 LongTo CLI？

- **🎯 多模型支持**：集成 GLM、Qwen 等多种 AI 模型，满足不同场景需求
- **🧠 强大的上下文理解**：支持大上下文窗口，处理复杂代码库和长文档
- **🔧 内置工具集**：文件操作、Shell 命令、网络获取、代码搜索等开发必备工具
- **🔌 可扩展架构**：支持 MCP (Model Context Protocol) 自定义集成
- **💻 终端优先**：为习惯命令行的开发者量身设计
- **🛡️ 开源安全**：Apache 2.0 许可，完全开源
- **🌏 中文优化**：专为中文用户优化的交互体验

## 📦 安装

### 快速安装

#### 使用 npx 直接运行（无需安装）

```bash
npx https://github.com/LongToon/LongTo
```

#### 使用 npm 全局安装

```bash
npm install -g @LongTo/LongTo-Cli
```

#### 系统要求

- Node.js 20 或更高版本
- macOS、Linux 或 Windows

## 📋 核心功能

### 代码理解与生成

- 查询和编辑大型代码库
- 使用多模态能力从 PDF、图像或草图生成新应用
- 用自然语言调试问题和故障排除

### 自动化与集成

- 自动化操作任务，如查询拉取请求或处理复杂的 rebase
- 使用 MCP 服务器连接新功能
- 在脚本中非交互式运行，实现工作流自动化

### 高级能力

- 内置网络搜索功能，获取实时信息
- 对话检查点，保存和恢复复杂会话
- 自定义上下文文件 (LONGTO.md)，为您的项目定制行为

## 🔐 认证选项

选择最适合您需求的认证方式：

### 选项 1：GLM API Key

**✨ 适合：** 需要中文优化的 AI 模型的开发者和用户

**优势：**

- **中文优化**：专为中文场景优化的模型
- **稳定可靠**：高可用性和稳定性
- **简单易用**：只需 API 密钥即可使用

```bash
# 获取您的 GLM API 密钥
export GLM_API_KEY="YOUR_API_KEY"
longto
```

### 选项 2：Qwen API Key

**✨ 适合：** 需要高性能中文模型的企业和团队

**优势：**

- **高性能**：强大的中文理解和生成能力
- **企业级**：适合企业级应用场景
- **多场景**：支持多种应用场景

```bash
# 获取您的 Qwen API 密钥
export QWEN_API_KEY="YOUR_API_KEY"
longto
```

### 选项 3：其他认证方式

项目还支持其他认证方式（如 Google OAuth、Gemini API Key、Vertex AI），这些功能已保留在代码中但默认不在界面显示。如有需要，可以通过配置启用。

## 🚀 快速开始

### 基本用法

#### 在当前目录启动

```bash
longto
```

## 📄 法律信息

- **许可证**：[Apache 许可证 2.0](LICENSE)
- **服务条款**：[条款与隐私](./docs/tos-privacy.md)
- **安全**：[安全政策](SECURITY.md)

---

<p align="center">
  由 LongTo 团队和开源社区用 ❤️ 构建
</p>
