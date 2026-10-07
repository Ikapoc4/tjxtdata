# tjxtdata — 天机学堂 AI 助手课程资料

2026 最新版 AI《天机学堂》项目实战的配套资料与源码。

## 目录结构

| 路径 | 说明 |
| --- | --- |
| `代码/tjxt.zip` | 项目源码压缩包（解压后为 `tjxt-javaai02/`，1608 个文件，约 3.57 MB） |
| `代码/gitee仓库代码地址.txt` | 官方 Gitee 仓库地址 |
| `讲义/在线讲义.txt` | 在线讲义地址 |
| `资料/prd/` | 产品需求文档（天机 agent V0.3） |
| `资料/设计稿/` | 设计稿（天机 AI 助手） |
| `资料/idea/` | IDEA 相关工具 |
| `资料/jdk17/` | JDK 17 下载地址信息 |
| `资料/虚拟机下载地址.txt` | 虚拟机镜像下载地址 |
| `网盘链接易失效，其余资料下载看此文档.doc` | 网盘资料说明 |

## 源码说明

`代码/tjxt.zip` 解压后为 `tjxt-javaai02/`，是 Spring Cloud 微服务项目，共 20 个顶级模块：

- **AI 相关**：`tj-aigc`（Spring AI 智能体服务 —— 对话、会话记忆、RAG 知识库、多智能体协同、语音转文字 / 文字转语音）
- **业务微服务**：`tj-course`、`tj-learning`、`tj-exam`、`tj-pay`、`tj-trade`、`tj-promotion`、`tj-search`、`tj-media`、`tj-message`、`tj-remark`、`tj-user`、`tj-data`
- **基础设施**：`tj-gateway`（网关）、`tj-auth`（认证）、`tj-common`（公共模块）、`tj-api`（Feign 接口）

## 未包含的内容

以下内容因超出 GitHub 限制**未上传**，请从网盘获取：

| 内容 | 大小 | 原因 |
| --- | --- | --- |
| `视频/`（106 个课程视频） | 约 4.67 GB | 仓库容量 |
| `资料/idea/ideaIU-2024.1.exe` | 951 MB | 单文件超 100 MB |
| `资料/jdk17/openjdk-17.0.2.zip` | 178 MB | 单文件超 100 MB |

> GitHub 限制：单个文件最大 100 MB，单次推送约 2 GB，仓库建议小于 1 GB。

## 获取项目

```bash
git clone https://github.com/Ikapoc4/tjxtdata.git
```

解压源码：

```bash
cd 代码
unzip tjxt.zip
```
