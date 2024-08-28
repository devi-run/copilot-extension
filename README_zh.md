<div align="center">

# 什么是代维（devi）？
[产品主页](https://github.com/devi-run/devi-github-copilot-extension) | [文档](./docs/content/zh/_index.md) | [新手指南](./docs/content/zh/copilot/_index.md) | [English](README.md)

Devi 是 **AI 智能体（Agent） 基础组件库**。构建基于智能体的生成式AI应用需要开发者完成很多基础组件的搭建工作，我们希望通过构建一系列通用的  AI 智能体 组件来简化开发人员使用生成式AI的复杂度。

![devi](https://aiseartifacts.blob.core.windows.net/devi/images/devi-title-logo.png)

</div>

# GitHub Copilot 中的devi插件

**Devi for GitHub Copilot** 是构建在 GitHub Copilot 生态体系上的一系列 AI智能体，devi提供了这些智能体的原子能力，并通过 GitHub Copilot Chat 为开发者提供服务。
代维DB智能体（devi DB agent）是我们首批发布的智能体组件，可以为开发者提供智能数据库问答和 Text2SQL 的自然语言数据库查询能力。

> 注意：由于这是一个GitHub Copilot扩展，您需要在Visual Studio Code中安装GitHub Copilot才能使用此扩展。Devi本身是一个免费扩展，但您需要为GitHub Copilot订阅付费。

演示视频 - B站：[代维(devi)数据库智能体 - GitHub Copilot扩展， 数据库智能问答，文本生成SQL脚本，一键生成数据库文档](https://www.bilibili.com/video/BV1XmsLepEdR/)

# 特性列表

开发者在GitHub Copilot Chat中使用 `@devi` 调用 代维DB智能体实现如下能力：

## 数据库智能问答
自动识别数据库结构，并允许用户使用自然语言对数据库提问，可以回答如下问题：
- 这个数据库是做什么用的？
- 哪些数据库对象之间存在联系？ 

 ![这个数据库是做什么用的？](https://aiseartifacts.blob.core.windows.net/devi/images/devi-zh-cn01.png)

 ![哪些数据库对象之间存在联系？](https://aiseartifacts.blob.core.windows.net/devi/images/devi-zh-cn02.png)

## 自然语言生成数据库查询（Text2SQL）
自然语言生成数据库查询（Text2SQL），用户可以使用自然语言提出问题，由AI根据数据库结构生成SQL语句
- 帮我生成所有应用和对应的review数量的汇总查询
- 帮我生成所有用户中发表review最多的用户的列表，按从多到少排序

![帮我生成所有应用和对应的review数量的汇总查询](https://aiseartifacts.blob.core.windows.net/devi/images/devi-zh-cn03.png)

![帮我生成所有用户中发表review最多的用户的列表，按从多到少排序](https://aiseartifacts.blob.core.windows.net/devi/images/devi-zh-cn04.png)

## 数据库文档生成
通过内置的 `@devi /docs <table_name>` 的快捷指令生成标准的额数据库文档

![@devi /docs <table_name>](https://aiseartifacts.blob.core.windows.net/devi/images/devi-zh-cn05.png)

完成上述步骤后，您可以通过键入 `@devi` 和您的查询开始在GitHub Copilot Chat中使用Devi DB智能体。

# 版权信息

Devi 相关的产品，资源，文档的版本均归[leansoftx.com]（https://leansoftx.com）所有。

未经书面授权，禁止使用任何与Devi相关的资源。