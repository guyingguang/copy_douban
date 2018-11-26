# 小程序防移动版豆瓣

采用[wepy](https://tencent.github.io/wepy/index.html)实现该应用，并实现部分功能

## 接口
只实现了影院热映一个[接口](http://douban.uieee.com/v2/movie/in_theaters)
采用promise和async/await 实现数据绑定.

头部菜单、电影和图书分别采用组件的形式实现，并采用[$emit进行组件之间的通信和交互](https://tencent.github.io/wepy/document.html#/?id=%E7%BB%84%E4%BB%B6%E9%80%9A%E4%BF%A1%E4%B8%8E%E4%BA%A4%E4%BA%92)

## 步骤

* 下载本源码，并找个趁手的IDE（vscode、webStorm、atom等）打开本项目
* 执行 `npm/cnpm install wepy` (如没有npm，请自行百度/google)
* 执行 `npm install`
* 下载微信开发工具，并打开本项目
* 执行`wepy build --watch`后，可实时在微信开发工具中预览

## 问题

程序内容、图片均来自豆瓣，如有问题，请告知，会及时删除本源码。
