# Devi - 文档

## 什么是代维（devi）？

Devi 是 **AI 智能体（Agent） 基础组件库**。构建基于智能体的生成式AI应用需要开发者完成很多基础组件的搭建工作，我们希望通过构建一系列通用的  **AI智能体组件** 来简化开发人员使用生成式AI的复杂度。

## 开始使用Devi

Devi 提供2种方式供开发者使用：第一种是通过 **GitHub Copilot 插件** 的形式提供开箱即用的体验 ，第二种是通过 **Devi NPM Package** 的方式提供更多的自定义能力。

### GitHub Copilot 插件

**Devi for GitHub Copilot** 是构建在 GitHub Copilot 生态体系上的一系列 AI智能体，devi提供了这些智能体的原子能力，并通过 GitHub Copilot Chat 为开发者提供服务。开发者可以通过 Visual Studio Marketplace 安装 Devi 插件，然后在 GitHub Copilot Chat 中使用 `@devi` 调用 代维DB智能体实现开箱即用的能力，比如：数据库对话、Text2SQL、数据库文档生成等。

- [Devi for GitHub Copilot 下载链接](https://marketplace.visualstudio.com/items?itemName=leansoftx.leansoftx-devi-copilot)
- 或者您也可以通过 Visual Studio Code 的插件商店搜索 `Devi` 安装。

有关如何使用 Devi for GitHub Copilot 的详细信息，请参考 [Devi for GitHub Copilot 操作手册](./copilot/_index.md)

### Devi NPM Package

**Devi NPM Package** 提供 `AI智能体` 的原子能力，开发者可以通过 NPM 安装 Devi Package，然后在自己的应用中使用 Devi 提供的能力。

- 具体使用方法请参考 [Devi NPM Package](https://www.npmjs.com/package/leansoftx-devi)
