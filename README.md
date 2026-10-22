# 拉卡拉交易接入 Skills

> **最新版 Skills：v0.4.19** · [完整审阅包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.19/lakala-payment-skills-0.4.19.zip) · [Agent Skill](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.19/lakala-payment-integration-0.4.19.zip) · [WorkBuddy / 豆包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.19/lakala-payment-workbuddy-0.4.19.zip) · [只读版](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.19/lakala-payment-readonly-0.4.19.zip) · [哈希与验证记录](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.19/release-0.4.19.json)

0.4.19 把聚合收银台 `vpos_id` 明确为多套终端时的实际支付路由字段，并修正随包 SDK 注释与示例。新增单独的 **SIT 测试环境演示经验**，记录两份真实验收报告中的参数选择、首个只读请求、出口 IP、回调隧道生命周期与 503、报文形态、退款和验签踩坑。SIT 演示经验与生产配置分开说明；Skills、SDK 和 Demo 不预置客户测试商户号、终端号或密钥。

## WorkBuddy / 豆包 MCP 连接器

[下载连接器 0.1.0](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/lakala-workbuddy-connector-0.1.0.zip) · [安装说明与独立发布页](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/tag/workbuddy-connector-v0.1.0)。连接器与 Skills 分开迭代。

## 验证

0.4.19 Agent Skill 与 WorkBuddy Node starter 各 68 项离线测试通过；完整包链接、schema、SDK 适配、ZIP 完整性与测试参数扫描通过。整合的 SIT 实测信息来自用户提供的 WorkBuddy 和豆包工作验收报告；本次构建没有另行向 SIT 发请求。Java/PHP 编译未执行。离线验证不等于新的 SIT 联调或生产准入。
