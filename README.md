# QQAlive

QQAlive 是一个规划中的开源 QQ AI 群友项目：使用腾讯官方 QQ 机器人接入，逐步构建可扩展的 Agent、群聊社交和多模态能力。

**当前状态：项目初始化与方案记录。尚未实现或验证 QQ、Codex、记忆、语音或图片功能。**

## 路线

- **V0：集成验证。** 使用 DeepSeek Harness 和腾讯官方 QQ 插件，验证 QQ 私聊、群 @、Codex 模型、会话上下文和权限隔离。
- **V1：独立项目。** 以腾讯官方 Node.js SDK 为通道，构建模型路由和社交引擎；长期记忆、TTS、AI 唱歌和图片生成作为独立能力逐步接入。

详见 [路线与验收](docs/roadmap.md)。接入配置和真实功能必须经过实际测试，不能以本文档作为运行成功的证明。

## 参考

- [腾讯 QQ 开放平台](https://q.qq.com/)
- [腾讯官方 DSH QQ 插件](https://github.com/tencent-connect/dsh-qqbot)
- [腾讯官方 QQ Bot Node.js SDK](https://github.com/tencent-connect/qqbot-nodejs)
- [第三方 Codex 订阅插件](https://github.com/WSL043/dsh-codex-subscription)

本项目与上述项目及其运营方无官方关联。第三方插件的安全性、兼容性及账号使用条件需要在部署前自行核实。
