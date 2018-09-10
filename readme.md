# react-proto-zh [![explain]][source] [![translate-svg]][translate-list]

[explain]: http://llever.com/explain.svg
[source]: https://github.com/chinanf-boy/Source-Explain
[translate-svg]: http://llever.com/translate.svg
[translate-list]: https://github.com/chinanf-boy/chinese-translate-list

「 为开发人员和设计人员提供React应用程序原型设计工具。 」

[中文](./readme.md) | ~~[english](./readme.en.md)~~


---

## 校对 ✅

<!-- doc-templite START generated -->
<!-- repo = 'React-Proto/react-proto' -->
<!-- commit = '0d3fa9f22640bd743e12fa34bc124aef7a3575b9' -->
<!-- time = '2018 9.7' -->
翻译的原文 | 与日期 | 最新更新 | 更多
---|---|---|---
[commit] | ⏰ 2018 9.7 | ![last] | [中文翻译][translate-list]

[last]: https://img.shields.io/github/last-commit/React-Proto/react-proto.svg
[commit]: https://github.com/React-Proto/react-proto/tree/0d3fa9f22640bd743e12fa34bc124aef7a3575b9
<!-- doc-templite END generated -->

### 贡献

欢迎 👏 勘误/校对/更新贡献 😊 [具体贡献请看](https://github.com/chinanf-boy/chinese-translate-list#贡献)

## 生活

[help me live , live need money 💰](https://github.com/chinanf-boy/live-need-money)

---

# 反应原[![Build Status](https://travis-ci.com/React-Proto/react-proto.svg?branch=master)](https://travis-ci.com/React-Proto/react-proto) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<img src="https://github.com/React-Proto/react-proto/blob/master/src/public/icons/png/64x64.png"/>
 
[React-Proto](https://react-proto.github.io/react-proto/) is a React application prototyping tool for developers and designers.

React-Proto允许用户预先可视化/设置他们的应用程序体系结构,并将该体系结构作为应用程序文件弹出到以前的项目或新的create-react-app项目或来自任何存储库的启动器模板中. 

下载用于[MacOS](https://github.com/React-Proto/react-proto/releases/download/v1.0.0/React-Proto-1.0.0.dmg),[Windows](https://github.com/React-Proto/react-proto/releases/download/v1.0.0/React-Proto.Web.Setup.1.0.0.exe),[Linux](https://github.com/React-Proto/react-proto/releases/download/v1.0.0/react-proto_1.0.0_amd64.deb).

-   Mac用户: 现在你可能需要进入你的安全设置,以允许应用程序在您的系统上运行,因为我们还没有苹果的许可证. 

如果你发现任何问题,[file issue](https://github.com/React-Proto/react-proto/issues)

## 如何使用

-   应用程序可以从CLI使用`react-proto`命令或单击应用程序图标. 

-   要启动一个新项目,要么导入模型,要么从空白阶段开始. 

-   添加要使用输入创建的组件,然后将组件框架拖到适当位置并相应地调整大小. 

<img src="https://github.com/React-Proto/react-proto/blob/master/assets/dragging.gif?raw=true"/>

-   在构建时,可以使用工具栏中的图标进行缩放ㄡ切换阶段的可拖动性ㄡ更新或删除图像ㄡ折叠左容器ㄡ以及导出文件. 

-   对于每个组件,您都有能力定义组件是否具有状态ㄡ框架组件的颜色以及应用父组件的能力. 

-   如果将容器放在其他组件周围,并且不能再访问它们,则可以使用相应下拉菜单中的层按钮来更改层顺序. 

<img src="https://github.com/React-Proto/react-proto/blob/master/assets/hierarchy.gif?raw=true"/>

-   在正确的容器中,PROPS选项卡允许您在关键值对中定义道具,以及必要的支柱类型. 

-   完成后,可以使用工具栏中的"导出"按钮从三个选项中选择如何导出文件: 
    1.  将文件导入到现有项目中. 只需选择要创建组件文件夹的路径即可. 
    2.  使用创建反应应用程序启动一个新项目 (项目将在"ProtoGyApp"下) . 
    3.  克隆你最喜欢的GITHUB RePo,用你最喜欢的启动文件启动一个项目. 

<img src="https://github.com/React-Proto/react-proto/blob/master/assets/export.gif?raw=true"/>

-   最后,开始建造!

## 作者

[Blessing E Ebowe](https://www.linkedin.com/in/blessingebowe/) [@refinedblessing](https://github.com/refinedblessing)

[Brian Taylor](https://www.linkedin.com/in/brianwtaylor/) [@brianwtaylor](https://github.com/brianwtaylor)

[Erik Guntner](https://www.linkedin.com/in/erik-guntner-9aa324b9/) [@erikguntner](https://github.com/erikguntner)

## 运行自己的版本

-   **叉子**和**克隆**储存库. 

-   打开项目目录

```bash
cd react-proto
```

-   安装依赖项

```bash
yarn install
```

-   运行应用程序

```bash
yarn start
```

-   为了发展经验ⅆ

```bash
yarn dev
```

-   在另一个终端

```bash
yarn electron
```

## 掉毛

```bash
yarn linter
```

## 测试

```bash
yarn test
```

## 内置

-   [React](https://reactjs.org/)-构建用户界面的框架. 
-   [Redux](https://redux.js.org/)JavaScript应用程序的可预测状态容器. 
-   [Electron](https://electronjs.org/)跨平台的桌面应用程序,包括HTMLㄡCSS和JS. 
-   [KonvaJS](https://konvajs.github.io/)HTML52D画布库用于桌面和移动应用程序. 
-   [React-Sortable-Tree](https://github.com/frontend-collective/react-sortable-tree#options)-为嵌套数据和层次结构拖放可分拣组件. 

## 致谢

### 标志设计

[Clariz Mariano](www.clarizmariano.com) [@havengoer](https://github.com/havengoer)

[Joe Thel](https://www.linkedin.com/in/joe-thel/) [@fakemonster](https://github.com/fakemonster)

## 许可证

这个项目是在麻省理工学院许可证下授权的. [LICENSE.md](https://github.com/React-Proto/react-proto/blob/master/LICENSE.md)文件以获取详细信息. 

## License

MIT © [chinanf-boy](http://llever.com)
