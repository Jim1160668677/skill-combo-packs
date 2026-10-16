# 支付链组合包与专家包

本目录只收录本地归档中已改造的组合包和专家包。ZIP 的版本、字节数、SHA-256 与状态见 [manifest.csv](manifest.csv)。

## 内容

- 账号二：6 个组合 Skill 包，见 [account2-combos](account2-combos/)。
- 账号二：12 个专家包，见 [account2-expert-packs](account2-expert-packs/)。
- 账号三：7 个 SkillPay 专家组合包，见 [account3-expert-bundles](account3-expert-bundles/)。

此前误纳入的 36 个单项创作者 Skill 和免费示例已从当前仓库版本移除；它们不属于本次确认的组合包/专家包范围。

## 已知状态

- 账号二 12 个专家包的 2026-10-09 上传记录标为 SkillHub listed / platform_review。对应本地清单同时标记 production_eligible=false、runtime_tested=false；上传或在架记录不代表生产调用已经验收。
- 账号三 7 个包的 2026-10-12 商品计划说明包内含按次调用契约，但商品层仍待定价后上架，尚不能据此说这些商品已上线。
- 三账号快照中定价字段本身不代表已开通服务化；截至本地快照记录，isServiceized 仍为 false。账号二组合包的生产运行状态也未在本归档中验证。

## 付费调用说明

GitHub 只保存文件，不托管 Skill 执行，也不会代收调用费。要让他人付费调用，还需要运行中的计费网关、服务端执行器和服务注册、调用平台服务化配置，以及一次端到端付款验证。仓库保持私有，外部使用者需要先获得仓库访问权限。

不要提交钱包凭据、访问令牌、Payment-Proof 或私有订单状态。
