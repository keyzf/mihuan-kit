# mihuan-kit

通用、易用、强大的可视化
`模型管理`、`文档生成`、`接口代理`、`数据库创建`、`后端代码自动生成`
开发工具包

## 项目目标

- 通用，普遍适用各种开发项目
- 易用，精简配置及依赖，开箱即用
- 强大，包含整套的模型管理、文档生成、接口代理、数据库创建、后端代码自动生成等众多功能
- 可视化，良好的UI操作界面

## 主要功能及模块

- 可视化的操作界面
  - 考虑使用`nodejs`+`Electron`/`nw.js`，下策是使用一个h5页面
  - 视图优先考虑`Material Design`，或者`Ant Design`
- 模型管理
  - 轻易创建修改模型数据，文件存储，不依赖数据库
  - 提供部分通用的模型模板，快速修改构建
- 文档生成
  - 通过模型配置，自动生成开发文档
  - 提供文档自动部署功能
- 数据库创建
  - 依据模型自动生成数据库表
  - 可利用mock工具插入模拟数据
- 接口代理
  - 代理数据来源分：
    - 基于文档，可配置mock数据
    - 基于远程接口，纯代理模式
    - 基于数据库数据，直接对接数据库
  - 依据模型自动生成模型的增删改查接口
  - 可自定义接口，可调用其他接口，对数据处理并重包装
- 模拟数据自动生成
  - 整合`mock.js`
- 后端代码自动生成
  - 依据模型自动生成合乎规范的后端增删改查代码
    - `java`生成`Spring boot`代码
    - `python`生成`flask`或`django`代码
    - `nodejs`生成`express`、`koa`或`eggjs`代码
