# 入网后：申请Core 🆔 与 每月链上签到指南

Author | 小新
-|-
Reviewer | -

## 概述

节点通过审计入网后，你还需要完成以下步骤才能正式享受 PoWh 工作量证明激励：

1. **完成高级 KYC** — 实名认证，建立可信身份
2. **申请加入 Jouleverse Core** — 成为核心贡献者组的一员，获得 Core 🆔
3. **获取初始 GAS** — 为你的地址注入少量 J，以便进行链上操作
4. **每月链上签到** — 证明维护人活跃，持续享受激励

---

## 1. 完成高级 KYC

高级 KYC 是 Jouleverse 可信身份体系的一部分，所有核心贡献者均须完成。

👉 **[点此打开 KYC 登记表单](kyc-form.html)** — 填写后自动生成汇总信息，复制或直接通过邮件提交给审查员。

或者，你也可以直接填写[空投登记表（腾讯文档版）](https://docs.qq.com/form/page/DTEp2cEdsa0lTelB0)。

填写时请准备好：
- 你的节点信息（enode、IP 等）
- 签块地址（0x...）
- 个人身份信息（身份证、手机号等）

待审核通过后，你将进入下一步。

---

## 2. 申请加入 Jouleverse Core

完成高级 KYC 后，你需要正式申请加入核心贡献者组（Core）。

具体流程：

1. **在节点预备群（或 Core 群）中发言**，说明你已通过审计，请求加入 Core 组
2. **等待 Core 管理员或审计节点** 将你拉入 Core 群 / 授予 Core 身份
3. **获得 Core 🆔** — 这是一个你在 Jouleverse 生态中的身份标识

> 💡 Core 🆔 的格式一般为 `J+数字`，例如 `J25`。你的 Core 🆔 将用于 PoWh 统计表中的身份标识。

---

## 3. 获取初始 GAS（燃料费）

要进行链上签到，你的地址上需要有少量 J 作为燃料费（gas fee）。如果地址里还没有 J，可以通过以下方式获取：

### 方式一：通过行星系统冷启动（推荐新人）

Jouleverse 建立了"行星系统"来帮助新人。具体步骤：

1. 打开 [Jouleverse 行星系统](https://github.com/Jouleverse/planetary-system/blob/main/README.md)，选择任意一位星球球长
2. 添加球长的微信，申请加入 TA 管理的星球
3. 完成 [JTI 可信身份认证](https://github.com/Jouleverse/jti2/blob/main/README.md)
4. 球长将向你的 web3 地址 **免费赠送 0.005 J**，足够用于签到等基础链上操作

### 方式二：自行 unwrap WJ

如果你已经持有 WJ（例如通过 PoWh 空投获得）：

1. 打开 [Jouleverse 区块链浏览器](https://jscan.jnsdao.com)
2. 搜索你的地址，找到 WJ 余额
3. 点击 WJ 余额旁边的 【unwrap】按钮
4. 输入要提取的 J 数量（仅提取少量即可，如 0.001 J）
5. 确认并签名上链

> ⚠️ 注意：提取 J 是不可逆的，提取后只能消耗不能移动，所以不要一次性提取过多。

---

## 4. 每月链上签到

### 为什么要签到？

链上签到是 PoWh 激励机制的核心环节。每个月你需要完成一次链上签到，以证明你的维护人身份仍然活跃。只有完成签到的贡献者，才能参与当月的 PoWh 激励分配。

### 签到前准备

- ✅ 你的地址上已有少量 J（参考第 3 节获取 GAS）
- ✅ 你的 Metamask（或其他 web3 钱包）已连接到 Jouleverse 主网
  - 网络名称：Jouleverse Mainnet
  - RPC：https://rpc.jnsdao.com:8503
  - Chain ID：3666
  - 代币符号：J

### 签到操作步骤

#### 方法一：通过区块链浏览器签到

1. 打开 [Jouleverse 区块链浏览器](https://jscan.jnsdao.com)
2. 连接你的钱包（点击右上角 【Connect Wallet】）
3. 导航至签到合约页面（通常在 PoWh 委员会公布的签到链接中操作）
4. 点击签到按钮，确认交易
5. 等待交易上链（约 10 秒）
6. 在区块链浏览器中搜索你的交易哈希，确认签到成功

#### 方法二：通过 PoWh 统计表核验

PoWh 委员会每月会发布[工作量统计表](https://github.com/Jouleverse/workspace)，统计表中会列出每位 Core 成员的签到状态。具体操作：

1. 在 PoWh 统计截止前完成链上签到
2. 你的签到记录会自动或由 PoWh 委员会核验后记录在统计表中
3. 可在 PoWh 统计表的"链上签到"列（AA 列）查看签到结果：签到成功填 "1"，未签到填 "0"

### 签到频率

- **每月至少签到 1 次**
- 建议设定每月提醒，避免漏签
- 漏签可能导致当月无法获得 PoWh 激励分配

---

## 常见问题

**Q: 签到一次大概需要多少 GAS？**
A: 链上签到属于简单的合约调用，gas 消耗很少，通常不到 0.0001 J，所以 0.005 J 足够签到几十次。

**Q: 忘记签到怎么办？**
A: 当月漏签会影响当月的 PoWh 激励分配。可以联系 PoWh 委员会说明情况，但建议养成每月签到的习惯。

**Q: 我还没有 Core 🆔，可以签到吗？**
A: 建议先完成高级 KYC 并申请 Core 🆔，因为签到记录需要与 Core 🆔 关联才能计入 PoWh 统计。

---

## 相关链接

- [Jouleverse 行星系统](https://github.com/Jouleverse/planetary-system/blob/main/README.md)
- [JTI 可信身份认证](https://github.com/Jouleverse/jti2/blob/main/README.md)
- [Jouleverse 区块链浏览器](https://jscan.jnsdao.com)
- [如何安装 MetaMask 并连接 Jouleverse](https://mp.weixin.qq.com/s/9TkupLVX1nqZlX4fz1TziA)
- [PoWh 工作量统计](https://github.com/Jouleverse/workspace)
- [如何向 Jouleverse Core 做贡献](https://how.jouleverse.com/#!contribute/how-to-contribute-to-core.md)
