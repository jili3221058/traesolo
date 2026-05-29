# OpenClaw 介绍

## 什么是 OpenClaw

OpenClaw（曾用名 ClawdBot、Moltbot）是一款采用 MIT 协议开源的 AI 智能体，由彼得·斯坦伯格（Peter Steinberger）开发。它是一款"行动型"智能体，运行在用户本地设备上，拥有系统级操作权限，能够通过即时通讯软件接收指令，自主执行文件管理、邮件处理、代码编写、浏览器自动化等真实世界任务。

## 核心功能

1. **本地系统操作**：拥有本地设备的系统级权限，可以读写文件、执行 Shell 命令、运行脚本、安装软件
2. **多渠道消息接入**：支持 WhatsApp、Telegram、Discord、Slack、Signal、iMessage、企业微信、QQ、飞书等平台
3. **浏览器自动化**：控制浏览器进行网页浏览、表单填写、数据抓取、截图等操作
4. **持久化记忆**：跨会话记忆能力，将用户信息、使用偏好、项目上下文写入本地 Markdown 文件
5. **技能包扩展**：通过安装社区开发的 Skills 快速获得新能力
6. **多模型支持**：不绑定特定大模型，支持国内外主流大模型及本地模型

## 支持的大模型

### 国际主流模型
- Anthropic Claude 系列
- OpenAI GPT 系列
- Google Gemini 系列
- xAI Grok 系列
- Meta Llama 系列

### 国内主流模型
- DeepSeek 系列
- 智谱 GLM 系列
- MiniMax 系列
- 腾讯混元系列
- 字节豆包系列

## 快速开始

```bash
npm install -g openclaw@latest
openclaw onboard --install-daemon
openclaw dashboard
```

## 官方链接

- 官网：https://openclaw.ai
- 文档：https://docs.openclaw.ai
- GitHub：https://github.com/openclaw
