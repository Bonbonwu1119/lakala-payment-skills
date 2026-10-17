# 拉卡拉交易接入 Skills

客户下载入口：[GitHub Release v0.3.7](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/tag/v0.3.7)。

## 下载

- [完整交付包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.3.7/lakala-payment-skills-0.3.7.zip)：源码、参考资料、错误码快照和离线验证脚本。
- [Agent Skill 集成包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.3.7/lakala-payment-integration-0.3.7.zip)：导入完整目录，ZIP 根目录含 `SKILL.md` 和 Node HTTP 发送器。
- [WorkBuddy / 豆包类 Agent 包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.3.7/lakala-payment-workbuddy-0.3.7.zip)。
- [只读包](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.3.7/lakala-payment-readonly-0.3.7.zip)：自包含单文件 `SKILL.md`，不含可执行发送器。
- [SHA-256 校验记录](https://github.com/Bonbonwu1119/lakala-payment-skills/releases/download/v0.3.7/release-0.3.7.json)。

## 版本与验证

0.3.7 修复了“只生成请求、无法发送”的问题：Node 20+ starter 提供显式环境选址、签名 POST 和响应验签。67 项离线测试使用模拟响应，不访问拉卡拉。发送器需客户自己的服务端代码显式调用，并由客户安全加载已授权凭据；生产请求有显式开关，Agent 缺少运行环境或密钥时不能自行请求。

错误码快照包含 2320 条记录、236 个错误码；诊断测试 21 项通过。知识库快照由用户提供，不代表拉卡拉官方实时规则或生产联调结论。收银台创建完整 URL 和部分合同仍需按客户当前官方资料核实。生产使用前须按客户获授权的测试流程完成接口、证书和资金状态核验。原始 CSV 未发布。
