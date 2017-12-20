# Material Design Toolkit

Sketch 版本要求：Sketch 48.1。我会在第一时间更新 Sketch 的版本，如果你在使用旧版，可能无法使用最新的版本，我尽量在每次更新之前都打包一次。

Material Design Toolkit（简称 MDT）是一套基于 Material Design 规范来设计的 Sketch Library，其目的是为了做快速原型，之所以选择 Material Design 是因为其拥有完整的规范，不需要在规范的细节上在重新设计，可以让我更关注与整体的应用，另外也是因为 Material Design 是目前为止最适合跨多个平台的设计方案。

所有的组件均按照 Material Design 官方规范来制作，但并不是完全一样，我会加入一些官方没有组件，以应对更复杂的系统设计，例如列表构造器等。有时候一些组件也会跟官方的有所不同，考虑到纯 CSS 环境下的可用性。例如文本框组件，保留了 MD 旧版本中的一些组建和 MD 中没有的 label 组件。

MDT 也可以用来做 UI 设计，但如果你使用 Measure 来导出作为标记，那可能会出问题，一个解决方案是把 Symbol 解锁变成普通的图层，这是 Measure 自身的局限性。

## 当前进度

除了继续完善各个组件之外，我想把每个组件具体的使用方法也补充在每个 Sketch 文件中，本来打算写成 Wiki，不过没时间做那么多，先放到单独的文件中，也可以离线使用。

![使用手册示例](https://raw.githubusercontent.com/jay1803/Material-Design-Toolkit/master/statics/manual.png?raw=true)

### 各组件说明

* Assets：基本组件，包括一些基本的颜色设置、网格系统等，如果要使用其他组建，则该组建也必须一起开启；
* Buttons：按钮组件，包括各种按钮和标签，按钮组件的颜色和文本应用了 Assets 中的颜色和文本；
* Cards：卡片组件，
* Dialogs：对话框组件，
* Forms：表单组件，包括文本框、单项选择和多项选择、日期选择器等；
* Icons：图标组件，该组件有点丧心病狂，包含了可能超过 1000 个图标组件，请谨慎使用，会卡机；
* Lists：列表组件，包括了常用的列表和列表控制器，以及类似列表的菜单；
* Toolbars：工具栏组件，包括了应用栏、导航栏和其他导航以及指示性的组件；
* Typography：排版组件，通过 Sketch Toolkit 插件自动生成的排版规模，包含了 MD 中常用的文字样式；
* Wireframe：线框图，是一个独立的文件，本来打算用来做一个更简单的组件，目前没有更新计划；

### 各组件完成进度

- [ ] Assets：虽其他组件更新，可能需要更新 icon 部分；
- [ ] Buttons：90%，基本完成，近期不会有更改；
- [ ] Cards：20%，一些常用的组合会被加入；
- [ ] Dialogs：20%，一些常用的对话框组合会被加入；
- [ ] Forms：70%，列表构造器和其他负责的也会加入；
- [x] Icons：100%，目前每个更新的计划；
- [ ] Lists：90%，不会有新的组件加入，可能会有组件的更改；
- [ ] Toolbars：70%，导航可能会有更新，抽屉导航也需要更新；
- [x] Typography：100%，目前没有更新计划；
- [x] Wireframe：100%，目前没有更新计划；

***

Sketch 的 git 提交是个很大问题，目前并没有很好的解决方案，第三方的服务也有很大的问题。因此这需要合作讨论才能解决。你可以在这里加入 Slack 讨论组：[MDSL-GIT](https://join.slack.com/t/mdsl-git/shared_invite/enQtMjg5MjE0OTc3MTA3LTJlMmQ4MDNmYTA4NzIzZGYyOWRmYmMyMDNjYmZlNjI4MTNlMmM1MjExY2RmOGVhODA2Yzc3MWNmY2NlNGUzYzc)。
