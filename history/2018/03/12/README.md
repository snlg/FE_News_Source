
> # XD-Daily-Front-End-News

## framework

- [react-redux源码解读](http://www.ayqy.net/blog/react-redux%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB/)：react-redux作为胶水一样的东西，似乎没有深入了解的必要，但实际上，作为数据层（redux）与UI层（react）的连接处，其实现细节对整体性能有着决定性的影响。组件树胡乱update的成本，要比多跑几遍reducer树的成本高得多，所以有必要了解其实现细节

- [react-router源码解读](https://www.jianshu.com/p/27ee7df4ccc1)：如果你已经是一个正在开发中的react应用，想要引入更好的管理路由功能。那么，react-router是你最好的选择~
react-router版本现今已经到4.0.0了，而上一个稳定版本还是2.8.1。相信我，如果你的项目中已经在使用react-router之前的版本，那一定要慎重的更新，因为新的版本是一次非常大的改动，如果你要更新，工作量并不小。
这篇文章不讨论版本的变化，只是讨论一下React-router4.0的用法和源码。

## CSS

- [移动端适配之flexible](https://github.com/amfe/article/issues/17)：曾几何时为了兼容IE低版本浏览器而头痛，以为到Mobile时代可以跟这些麻烦说拜拜。可没想到到了移动时代，为了处理各终端的适配而乱了手脚。对于混迹各社区的偶，时常发现大家拿手机淘宝的H5页面做讨论——手淘的H5页面是如何实现多终端的适配？

- [移动端适配之vw](https://juejin.im/entry/59226177128fe1005c2cd172)：响应式布局的实现依靠媒体查询（ Media Queries ）来实现，选取主流设备宽度尺寸作为断点针对性写额外的样式进行适配，但这样做会比较麻烦，只能在选取的几个主流设备尺寸下呈现完美适配。

## webpack

- [webpack详解](https://juejin.im/post/5aa3d2056fb9a028c36868aa?utm_medium=fe&utm_source=weixinqun)：webpack是现代前端开发中最火的模块打包工具，只需要通过简单的配置，便可以完成模块的加载和打包。那它是怎么做到通过对一些插件的配置，便可以轻松实现对代码的构建呢？

