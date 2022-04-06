# XD RiFriends 社群发布库

- [XD RiFriends 社群发布库](#xd-rifriends-社群发布库)
  - [社群信息](#社群信息)
  - [Minecraft 社区服务器信息](#minecraft-社区服务器信息)
    - [服务器结构示意图](#服务器结构示意图)
    - [客户端下载地址](#客户端下载地址)
    - [服务器开发进度面板](#服务器开发进度面板)

该库用于存储社群中的知识库文件（流程图、Markdown等），同时在 `README.md` 中发布 Minecraft 客户端的下载地址。当然了，本发布库还会承载 issue(提供问题反馈) 以及 Kanban(开发进度展示) 功能。

## 社群信息

XD RiFriends QQ群：
XD RiFriends 开黑啦社群：
XD RiFriends 社群 Wolai 主页：

## Minecraft 社区服务器信息
### 服务器结构示意图

我们当前拥有两个正在运行的服务器，一个是我们的BC群组服，还有一个是独立的战争服。

```mermaid
graph LR;
    Main-->War_Server
    Main-->BC_Lobby_Server
    subgraph XD_RiFriends BC 群组服
    BC_Lobby_Server-->BC_MiniGames_Server
    BC_Lobby_Server-->BC_Survival_Server
    end
```
### 客户端下载地址

群组服客户端：

战争服客户端：

### 服务器开发进度面板

群组服：https://github.com/snjjnlk/XD_RiFriends_Publish/projects/1

战争服：https://github.com/snjjnlk/XD_RiFriends_Publish/projects/2