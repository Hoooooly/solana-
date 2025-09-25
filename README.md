# solana-

# Anchor 学习闯关计划 ✅

## 关卡 0 — 环境准备
- [x] 安装 Rust、Solana CLI、Anchor CLI、Node.js
- [x] 运行 `solana-test-validator`
- [x] 用 `anchor new hello_anchor` 创建新项目并 `anchor build`

## 关卡 1 — 第一个 Anchor 程序（计数器）
- [ ] 在 `lib.rs` 中写 `initialize` 和 `increment` 指令
- [ ] 成功 `anchor build` 并 `anchor test`
- [ ] 能在测试中看到 `count` 从 0 → 1

## 关卡 2 — Accounts、约束与 PDA
- [ ] 理解 `#[derive(Accounts)]` 的基本约束
- [ ] 写一个用 PDA 初始化账户的例子
- [ ] 在 TS 端计算 PDA 并验证地址正确

## 关卡 3 — TypeScript 客户端
- [ ] 学会用 `@coral-xyz/anchor` 调用程序
- [ ] 成功在 TS 脚本中调用 `initialize`、`increment`
- [ ] 使用 `program.account.<Type>.fetch()` 读取数据

## 关卡 4 — SPL Token 交互 & CPI
- [ ] 写一个调用 Token Program 的指令（transfer/mint）
- [ ] 测试 Token 转账成功

## 关卡 5 — 测试、调试、CI
- [ ] 写完整的 Rust/TS 测试（包含错误路径）
- [ ] 在 GitHub Actions 中跑通 `anchor test`

## 关卡 6 — 安全与审计要点
- [ ] 学习常见约束（`has_one`、`owner`、`close`）
- [ ] 写一个错误输入触发约束失败的测试
- [ ] 阅读常见攻击案例并复现

## 关卡 7 — Zero-copy 与优化
- [ ] 用 `#[account(zero_copy)]` 重写一个 struct
- [ ] 比较 `space` 大小与性能差异

## 关卡 8 — 小型实战项目
- [ ] 选择一个 DApp（NFT 市场 / Escrow / 抵押）
- [ ] 实现核心逻辑 + TS/React 前端交互
- [ ] 写完整测试并在 devnet 跑通

## 关卡 9 — 进阶部署与升级
- [ ] 学习 Upgradeable Program 的机制
- [ ] 在 devnet 部署并演练 upgrade 流程
- [ ] 记录风险与安全注意事项
