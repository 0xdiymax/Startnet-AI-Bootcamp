

<div align="center">
    <h1>Startnet-AI-Bootcamp</h1>
    <p>Starknet AI Agent 开发者训练营 —— 由 Starknet 与 OpenBuild 强强联手打造，致力于为开发者打开通往 "区块链+AI" 创新领域的大门。
</p>
</div>


### [Github Discussion](https://github.com/openbuildxyz/Web3-Frontend-Bootcamp/discussions) 使用方法

| Categories         | Description                                                  |
| ------------------ | ------------------------------------------------------------ |
| [🍕Materials]( )         | 课外资料/课堂笔记（欢迎贡献）  |
| [🙏 Q&A]( )              | 提问 / 知识答疑   |
| [💰Bounty]( )   | Bounty 任务：课堂作业/课堂笔记/社区贡献etc|
| 💡[I've got an idea!]( )   | 关于一些 Amazing fancy ideas, 用来<br />1. Starknet AI Agent共学 <br />2. 组队开发<br />3. 参加黑客松<br />4. 招聘内推<br />5. 自娱自乐🎣<br /> |

### ⭐ 核心亮点 ⭐
🧙‍♂️ OpenBuild 技术导师 + 助教团队，小白友好型氛围
👩‍🏫 录播课 + 研讨会 + 免费知识库，学习灵活高效
🙌 免费学习 + 官方背书，资源丰富
✅ 认证证书，边学边提升竞争力

### ⭐ 学习大纲 ⭐

Session 1: Fundamentals 从 0-1 带你了解 Starknet 基础知识（[官网](https://openbuild.xyz/learn/challenges/2036589711/1716360050) | [哔站]() | [油管](https://www.youtube.com/watch?v=6T_NW733lbE)）

Session 2: Smart Contracts 智能合约（[官网](https://openbuild.xyz/learn/challenges/2036589711/1716360063) | [哔站]() | [油管](https://www.youtube.com/watch?v=sXKp87e30UE)）

Session 3: Testing Smart Contracts 智能合约实战（[官网](https://openbuild.xyz/learn/challenges/2063566106/1743337345) | [哔站]() | [油管](https://www.youtube.com/watch?v=_fafV7NXNhY)）

Session 4: Frontend 前端开发实战

Session 5: AI Agents 实战

## 参与方式

**⚠️⚠️⚠️ 请先完整地看完这部分内容再开始操作！**

1. 注册 [OpenBuild](https://openbuild.xyz) 账号；
2. 联系 **ZEPPELI_0709** 加入微信交流群；
3. 参考「[活动报名](#活动报名)」提交 PR，完成报名。

#### 前置操作

先点击页面顶部右上角的「Fork」在自己空间中创建备份，随后将备份仓库 `git clone` 至本地，接下来的所有操作请在自己的仓库内完成。

如果你不熟悉 Git 的操作，可以下载 [GitHub Desktop](https://desktop.github.com/)，使用 GUI 完成。

#### 活动报名

复制 `members` 文件夹中的 `github_id` 文件夹，将新文件夹名称改为自己的 GitHub ID，填写其中 `readme.md` 的信息，提交 PR，完成注册报名。

**不要把 `github_id` 文件夹删除了，只能提交自己新创建的文件夹！**

#### 课后作业

每节课都有相应的实战任务，需要在 `members/[github_id]` 文件夹下按照 `task[n]` 的命名方式创建任务文件夹，如：`task1`、`task2`。

任务代码必须全部开源公开，每个任务提交一次 PR。

### 提交规范

每完成一个任务，在你自己的仓库 `commit` 之后提交一个 `pull request`，只可以修改你自己的文件，不可修改其他人的文件。

**⚠️⚠️⚠️ 不符合规范的会加上「[invalid]标签，请按要求提交你的 PR！**

#### PR 命名

注册的 PR，命名为 `init: user-name`，例如 `init: Beavnvvv`

提交 task 的 PR，命名为 `task[n]: user-name`，例如： `task0: Beavnvvv`

需要编写网页的 `task`，请在描述中上传效果截图。

**请不要把报名和提交TASK的内容合并到一起，也不要将多个TASK放到一起提交！<br>请不要把报名和提交TASK的内容合并到一起，也不要将多个TASK放到一起提交！<br>请不要把报名和提交TASK的内容合并到一起，也不要将多个TASK放到一起提交！**

#### 开启多个 PR

很多人学习热情高涨，会迫不及待地把能做的任务都做了；但由于审核人员人手不够，PR 合并得会比较慢，若只是「单线程」地提交 PR 的话，影响学员的进度。

实际上是可以开启多个 PR 的，可「多线程」去完成任务——

将本仓库 fork 到自己空间后，基于 `main` 分支创建相应的功能分支，如：`init`、`task1`。

在功能分支完成对应任务后，发起 PR；切换到其他功能分支继续做任务，再发起 PR，如此往复。

## 任务说明 请仔细阅读要求

| 任务                                         | 名称         | 说明                     |
|:-------------------------------------------|------------|:-----------------------|
| [Task 1](task/01_React_To-Do-List.md)            | React To-Do-List | 开发一个待办事项应用            |
| [Task 2](task/02_Blockchain_Basic.md)            | Blockchain Basic | 区块链基础小测 |
| [Task 3](task/03_NFTMarket_Contract.md)              | NFTMarket Contract | 编写并部署一个NFTMarket的合约      |
| [Task 4](task/04_NFTMarket_Component.md)             | NFTMarket Components | 使用ethers.js和wagmi与NFTMarket合约交互         |
| [Task 5](task/05_NFTMarket_Dapp.md)             | NFTMarket Dapp  | 开发一个完整的NFTMarket的Dapp         |
| [Task 6](task/06_Uniswap_SDK.md)          | Uniswap SDK | 完成SDK学习，制作一个与uniswap交互的前端app    |
| [Task 7](task/07_EVM++_Demo.md)          | web3小工具实践 | 跟随[教程](https://fanatical-krypton-122.notion.site/OpenBuild-Frontend-Bootcamp-5e62657ab5774786b1901bfd862e8e9a?pvs=4)学习EVM++，实现一个限流器demo   |
| [Task 8](task/08_Hello_Morph.md)          | Hello Morph |  在Morph Holesky上部署任意合约并在Morph浏览器上验证   |
| [Task 9](task/09_Hello_TheGraph.md)          | Hello TheGraph |  为NFTMarket创建一个The Graph子图   |

## 参考资料

### 课前参考资料

1.[starknet-foundry](https://foundry-rs.github.io/starknet-foundry/)

### Web3 技术库

1. [WAGMi](https:///wagmi-xyz.vercel.app/)
2. [web3-react](https://github.com/Uniswap/web3-react)

### 实践参考

1. [Next.js Ethereum 脚手架](https://github.com/ChangoMan/nextjs-ethereum-starter)
2. [Uniswap](https://github.com/Uniswap/interface)

### 大牛学习心得

1. [Web3 DApp 最佳编程实践指南](https://guoyu.mirror.xyz/RD-xkpoxasAU7x5MIJmiCX4gll3Cs0pAd5iM258S1Ek)
2. [郭宇的 Web3 技术栈收藏](https://github.com/stars/guo-yu/lists/dapp-best-practice-stack)
