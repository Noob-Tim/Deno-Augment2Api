# Deno-Augment2Api
Deno-Augment2Api 是一个用于连接 Augment API 的中间层服务，提供 OpenAI 兼容的接口，支持 Claude 3.7 模型的调用。

## 使用方法
- fork 本仓库，在deno dashboard 部署

## 使用须知
- 使用本项目可能导致您的账号被标记、风控或封禁，请自行承担风险！
- 默认使用`Agent`模式，屏蔽所有工具调用，使用模型原生能力回答，否则对话会被工具调用截断


## 支持模型
```bash
传入模型名称以 -chat 结尾,使用CHAT模式回复

传入模型名称以 -agent 结尾,使用AGENT模式回复

其他模型名称默认使用CHAT模式
```
