> **软件开发 → Web3 后端/全栈开发工程师 → Web3 安全工程师**

**B 站完全有足够的免费资源，而且很多课程质量并不输付费训练营。**

我给你设计了一条 **3个月～6个月的学习路线图**，偏技术开发路线，不是炒币路线。

---

# 第一阶段：建立 Web3 世界观（1周）

目标：

* 搞懂区块链到底是什么
* 理解 BTC、ETH、钱包、Gas
* 理解智能合约和 DApp

推荐课程：

### Web3公开课

[B站课程：一个视频搞懂区块链、比特币和智能合约](https://www.bilibili.com/video/BV1Vz4y1a7GM/?utm_source=chatgpt.com)

重点看：

* 为什么要学习 Web3
* 区块链基础
* 钱包与账户
* 智能合约概念
* Web3 JavaScript 基础

课程内容覆盖区块链、钱包、账户、智能合约和前端交互，适合作为零基础入门。([哔哩哔哩][1])

---

# 第二阶段：Solidity 入门（2周）

目标：

能够自己写：

* ERC20
* NFT
* 简单质押合约
* 多签钱包

推荐课程：

### Patrick Collins 全栈 Solidity 课程（中文版）

[B站课程：32小时区块链、智能合约与全栈Web3开发](https://www.bilibili.com/video/BV1Ca411n7ta/?utm_source=chatgpt.com)

这是目前 B 站最值得看的免费 Solidity 课程之一。

内容包括：

* Solidity 基础
* Remix
* Hardhat
* EVM
* Chainlink
* DeFi
* NFT
* DAO
* 全栈 DApp

课程总时长超过 30 小时。([哔哩哔哩][2])

---

# 第三阶段：Foundry 开发框架（2周）

目标：

学会目前主流的智能合约开发方式。

现在很多项目已经：

Hardhat → Foundry

推荐：

### Foundry 全套课程

[B站课程：Foundry零基础教程](https://www.bilibili.com/video/BV13a4y1F7V3/?utm_source=chatgpt.com)

学习内容：

* Foundry
* Forge
* Cast
* Anvil
* 合约测试
* 主网 Fork 测试

覆盖区块链基础、Solidity、DApp 开发和 Foundry 工具链。([哔哩哔哩][3])

---

# 第四阶段：Web3 全栈开发（3周）

目标：

能做一个完整项目。

技术栈：

```text
Next.js
TypeScript
wagmi
viem
RainbowKit
Solidity
Foundry
```

学习顺序：

```text
钱包连接
↓
读取链上数据
↓
调用智能合约
↓
部署前端
```

继续跟着 Patrick Collins 课程后半部分即可。([哔哩哔哩][2])

---

# 第五阶段：DeFi 核心协议（2周）

目标：

看懂主流协议源码。

学习顺序：

```text
ERC20
↓
Uniswap V2
↓
Aave
↓
Compound
↓
MakerDAO
```

B站搜索：

* Uniswap V2源码解析
* Aave源码解析

同时阅读官方源码。

推荐先研究：

Uniswap Labs

再研究：

Aave Labs

---

# 第六阶段：Web3 安全（重点）

这一步最适合你。

你之前经常研究：

* 混币器
* 跨链桥
* 风控
* 交易追踪
* EVM

实际上已经接近安全方向。

学习内容：

## 常见漏洞

```text
重入攻击
权限控制错误
闪电贷攻击
价格预言机攻击
签名漏洞
Delegatecall漏洞
```

学习工具：

### Slither

Slither

这是目前最常用的智能合约静态分析工具之一。([arXiv][4])

---

## 审计框架

学习：

```text
Slither
Foundry Fuzz
Invariant Testing
Mythril
Echidna
```

---

# 第七阶段：Solana（可选）

如果你未来想做 Meme 发射器、机器人、量化交易。

建议单独开一条线：

```text
Rust
↓
Solana Program
↓
Anchor
↓
Jito
↓
Pump.fun生态
```

不要和 EVM 同时学。

---

# 推荐项目练习（简历级）

## 初级

### ERC20 发币平台

功能：

```text
创建代币
铸造
销毁
转账
```

---

## 中级

### 去中心化众筹

功能：

```text
创建项目
捐款
退款
提取资金
```

---

## 高级

### Mini Uniswap

功能：

```text
添加流动性
移除流动性
Swap
LP Token
```

---

## 安全方向

### Web3 风控系统（非常适合你）

技术栈：

```text
Node.js
NestJS
PostgreSQL
Redis
Ethers
```

功能：

```text
地址画像
风险评分
交易追踪
黑名单识别
资金流分析
```

这个项目的含金量通常比普通 DApp 更高。

---

# 最终学习路线

```text
Web3基础
    ↓
Solidity
    ↓
Foundry
    ↓
Web3全栈
    ↓
ERC20 / NFT
    ↓
DeFi源码
    ↓
安全审计
    ↓
风控系统
    ↓
Solana（可选）
```

按照每天 2~3 小时学习计算：

* 入门开发：第1~2个月
* 独立开发 DApp：第3个月
* 能看懂主流协议源码：第4个月
* 入门 Web3 安全审计：6个月左右

对于你目前已经有 Node.js、Next.js、区块链和风控背景，我建议直接从 **第二阶段 Solidity + 第三阶段 Foundry** 开始，第一阶段只花两三天补概念即可。

[1]: https://www.bilibili.com/video/BV1Vz4y1a7GM/?utm_source=chatgpt.com "〖web3公开课〗一个视频教你搞懂区块链、比特币和智能合约（不看后悔系列）_哔哩哔哩_bilibili"
[2]: https://www.bilibili.com/video/BV1Ca411n7ta/?utm_source=chatgpt.com "（32 小时最全课程）区块链，智能合约 & 全栈 Web3 开发_哔哩哔哩_bilibili"
[3]: https://www.bilibili.com/video/BV13a4y1F7V3/?utm_source=chatgpt.com "〖人工精翻〗B站最新Solidity智能合约Foundry框架零基础教程1-12课（已完结）_哔哩哔哩_bilibili"
[4]: https://arxiv.org/abs/1908.09878?utm_source=chatgpt.com "Slither: A Static Analysis Framework For Smart Contracts"
