# 拉卡拉交易接入 Skills

> **最新版 Skills：v0.4.18** · [完整审阅包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.18/lakala-payment-skills-0.4.18.zip) · [Agent Skill](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.18/lakala-payment-integration-0.4.18.zip) · [WorkBuddy / 豆包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.18/lakala-payment-workbuddy-0.4.18.zip) · [只读版](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.18/lakala-payment-readonly-0.4.18.zip) · [哈希与验证记录](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.18/release-0.4.18.json)

本版不在 Skill、SDK 或 Demo 中预置测试环境商户号、终端号、密钥或证书。只有确认 SIT 演示或请求后，Agent 才读取用户单独提供的本机参数文件，按接口选择对应商户/终端，并在请求前申明接口、商户号、终端字段和值及金额上限。随包 SDK/Demo 不含私钥和证书文件。

## WorkBuddy / 豆包 MCP 连接器

[下载连接器 0.1.0](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/lakala-workbuddy-connector-0.1.0.zip) · [安装说明与独立发布页](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/tag/workbuddy-connector-v0.1.0)。连接器与 Skills 分开迭代。

## 验证

0.4.18 的 Node starter 离线测试 90 项通过，错误码诊断测试 21 项通过；完整包、SDK endpoint、SDK adaptation 与 ZIP 内容校验通过。当前字段合同仍有官方核验缺口，Java DTO 的金额类型与退款通知必填性冲突已标记为待确认。离线结果不等于真实 SIT 联调或生产准入。
