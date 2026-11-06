# bsc-learn

阅读 [bnb-chain/bsc](https://github.com/bnb-chain/bsc) 节点源码时整理的学习笔记，做成了可交互的 HTML 页面。

| 文件 | 内容 |
|---|---|
| `bsc-architecture.html` | BSC 节点源码线路图：交易、出块、MEV、投票最终性、区块导入五条数据流，点站点可查看源码位置和原理；另有 Parlia 共识、区块头 Extra、系统交易、快速最终性、分叉选择、MEV、Payment Lane、网络、存储、硬分叉等章节 |
| `bsc-p2p-discovery.html` | 节点发现与连接：新节点从首次启动到连上第一个节点的 17 步分步时序图，候选节点要过的各道检查，以及路由表如何逐轮扩张 |

## 怎么看

克隆或下载仓库后，用浏览器直接打开 HTML 文件即可。两个页面之间有互相跳转的链接。

## 说明

- 内容基于 bnb-chain/bsc v1.8.2，commit `54afaff4d`（2026-11-03）。文中的源码行号只对这个 commit 有效。
- 页面字体从 Google Fonts 加载，离线打开时会改用系统字体，内容不受影响。
