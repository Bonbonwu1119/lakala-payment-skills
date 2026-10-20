# 拉卡拉交易接入 Skills

客户下载入口：[最新版 v0.4.17](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/tag/v0.4.17)。

## 下载 Skills

- [完整审阅包 0.4.17](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/lakala-payment-skills-0.4.17.zip)：源码、参考资料和离线验证脚本。
- [Agent Skill 集成包 0.4.17](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/lakala-payment-integration-0.4.17.zip)：集成 Skill 与发送器。
- [只读包 0.4.17](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/lakala-payment-readonly-0.4.17.zip)：只读单文件版。
- [0.4.17 校验记录](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.4.17/release-0.4.17.json)：文件哈希及随包检查记录。

## WorkBuddy / 豆包 MCP 连接器

如果要在 WorkBuddy 或豆包中通过 MCP 调用拉卡拉工具，请下载独立的[连接器 0.1.0 发布包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/workbuddy-connector-v0.1.0/lakala-workbuddy-connector-0.1.0.zip)，或查看[连接器发布说明与安装文件](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/tag/workbuddy-connector-v0.1.0)。这是普通 GitHub Release，不是预发布版；它与上面的 Skills ZIP 分开发布。

连接器经过本地协议与离线测试；尚未完成拉卡拉 SIT 真实请求。真实联调须从获准的中国境内网络进行，并按连接器文档配置环境与凭据。

## 版本与验证

0.4.17 的发布包哈希与清单一致；Node starter 离线测试 90 项通过，错误码诊断测试 21 项通过。离线测试使用模拟响应，不代表拉卡拉真实联调通过。
