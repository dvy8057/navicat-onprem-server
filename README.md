# Navicat On-Prem Server 永久授权 ¥530 起：本地化团队协作、数据不出内网、优惠码再省 5%

说来也是有意思。

前阵子帮一个客户调数据库环境，三个开发分在杭州、深圳、成都，每人手里都攥着一份 Navicat Premium，连接配置各存各的，查询脚本靠微信文件传来传去。等我把同一条 SQL 在三台机器上对了一下午，才反应过来——这事儿根本不该这么干。

这其实正是 Navicat On-Prem Server 想解决的问题。

简单讲，它是一套跑在你们自己服务器上的"私有云协作端"，团队所有人通过它同步连接设置、查询历史、模型工作区、BI 看板这些原本散落在各自本地的 Navicat 资源。最大的好处就一条：数据不离开你们公司那一墙之内，不经过任何第三方。

最近它刚升到 3.x，支持了 PostgreSQL 和 Fujitsu Enterprise Postgres，查询编辑器也加了代码补全、代码折叠和 SQL 美化。说实在的，做数据库工具这么多年，能在 on-prem 这条路上坚持更新的产品不多。

## 套餐价格对比：标准版 vs 非商业版

直接说价格，别绕弯子。On-Prem Server 的授权按"令牌（token）"卖，一个 token 对应一个 Navicat 客户端协作席位。授权类型主要看用途：个人学习用非商业版，公司项目用标准版。

下面这份对比表是数码荔枝的现行价格（已叠加优惠码 PCALL 9.5 折），可以直接点击购买：

| 授权类型 | 时长 | 原价（CNY） | PCALL 9.5 折 | 购买链接 |
| --- | --- | --- | --- | --- |
| 非商业版 | 3 个月 | ¥98 | ¥93.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |
| 非商业版 | 1 年 | ¥298 | ¥283.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |
| 非商业版 | 永久 | ¥558 | ¥530.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |
| 标准版 | 3 个月 | ¥198 | ¥188.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |
| 标准版 | 1 年 | ¥558 | ¥530.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |
| 标准版 | 永久 | ¥1198 | ¥1138.1 | [前往购买](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) |

可能你已经注意到了，标准版永久版折后 ¥1138.1，比一年标准版（¥530.1）只贵一倍出头。换句话说，打算用超过两年的团队，永久版基本就是省一整年。

> 提醒一下：非商业版只适合个人学习、学术研究、非盈利项目。在公司环境里哪怕只用一次，都算授权违规。公司项目请直接选标准版起步。

## 优惠码怎么用

下单流程很简单：

1. 进入 👉 [数码荔枝 Navicat On-Prem Server 页面](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj)
2. 选好授权规格，加入购物车
3. 结算时在「优惠码」一栏输入 **PCALL**
4. 系统自动按 9.5 折重算

PCALL 这个码在 Navicat 全系列通用，没有门槛，能和官方活动叠加。如果赶上促销季，叠加下来还能再低一点。

## 第三方测评说了什么

我们翻了翻 Navicat 官方 3.0 发布博客和 PostgreSQL 官网的通告。3.0 这一版最被业界点名的两件事，一是终于把 PostgreSQL 纳入 on-prem 协作生态——过去 On-Prem Server 主要服务 MySQL/MariaDB/MongoDB，PG 用户一直在外张望；二是查询编辑器的代码补全和折叠，对长时间写 SQL 的人来说，是从"能用"到"舒服"的关键一步。

PostgreSQL 官方在版本通告里也专门点名了这个变化，对用 PG 的团队算是个明确信号：这套协作方案终于正式覆盖到你们了。

至于用户口碑，主流反馈集中在两点：一是部署比想象中省心，按官方安装指南跑几条命令就能起服务；二是协作同步的延迟比走第三方云小很多，毕竟都在内网里来回。吐槽主要集中在英文文档和某些 Linux 发行版的依赖处理上，但都不是硬伤。

## 谁适合上这套

按我们看下来的经验，下面这几类团队装上之后收益最明显：

- **分布式开发团队**：成员在不同城市甚至不同时区，连接配置和查询历史需要统一管理
- **数据敏感型企业**：金融、医疗、政府类项目，数据合规要求禁止走第三方云
- **DBA 团队**：多人轮班管理同一组数据库，需要统一的操作历史和模型版本
- **重 Navicat 生态的团队**：已经在用 Premium、Data Modeler、BI 等多条产品线，协作需求自然产生

反过来，如果团队就一两个人、项目短期、对数据走云无所谓，那直接用 Navicat 自带的 Cloud 同步或免费 Lite 版就够，没必要上 On-Prem。

## 写在最后

工具这东西，值不值从来不是看价格标签，而是看它能不能把你从重复劳动里捞出来。

On-Prem Server 解决的不是"能不能连数据库"的问题——这事 Premium 自己就能干。它解决的是"三个人的连接配置为什么要对三遍"这种团队协作上的内耗。如果你的团队正在被这种内耗磨，那 ¥530 起的永久非商业版，或者 ¥1138 的标准永久版，可能就是今年最值的一笔工具预算。

下单入口在这：👉 [数码荔枝 Navicat On-Prem Server](https://lizhi.shop/products/navicat-on-prem-server?cid=7bbix2xj) ，别忘了结算时贴上 PCALL。
