RocketEngine
===

#### Notice: Io.js version at least v1.x

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/abbshr/RocketEngine?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

### fSlider_ws V0.5.x - RocketEngine

[![Package Quality](http://npm.packagequality.com/badge/rocket-engine.png)](http://packagequality.com/#?package=rocket-engine)

[![Build Status](https://travis-ci.org/abbshr/RocketEngine.svg?branch=master)](https://travis-ci.org/abbshr/RocketEngine)
[![npm version](https://badge.fury.io/js/rocket-engine.svg)](http://badge.fury.io/js/rocket-engine)

[![NPM](https://nodei.co/npm/rocket-engine.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/rocket-engine/)

#### Wiki & APIs:
**see the [WIKI](https://github.com/abbshr/RocketEngine/wiki/RocketEngine-V0.4.x--%E4%B8%AD%E6%96%87%E7%89%88Wiki) page to lookup the whole reference**

RocketEngine (原名fslider_ws)是一个Node.js的轻量级且人性化的WebSocket库。

+ 本着易于使用的原则，当然以容易使用为首～
+ 无论客户端还是服务器仅支持WebSocket协议，并且绝对轻量级。
+ 性能高不高，一试便知道～
+ 全面升级的事件驱动支持
+ 文本/二进制数据传输全部可用，而且提供了方便快捷的语法糖～
+ flexible的流式读写API
+ 命名空间支持，也就是说如果你想搞个多频道app，绝对没问题的～
+ 支持自定义事件（这个想法参考Socket.IO）
+ 自带配合Server的浏览器端框架(自v0.5.3之后将会自动挂载到Http路由, 无需额外添加)
+ 附带一个WebSocket non-browser客户端
+ 框架很小，不过功能可不弱哦～
+ 详细的日志输出
+ 无第三方模块依赖（依赖模块全是从这个项目分离出来的）
+ 适合newbies学习Node.js和WebSocket

#### 依赖模块

+ [event.js](https://github.com/abbshr/event.js): Node-style前端Pub/Sub事件驱动编程框架
+ [colorlogger](https://github.com/abbshr/colorlogger): 保存/加载/输出彩色终端日志

##### 项目状态

now in v0.5.x, implement streamming API, websocket server, websocket non-browser client and the security mechanism descripted in RFC 6455

##### Install

```sh
npm install rocket-engine
```

if you have clone this repo, just need to install dependencies:

```sh
npm install
```

##### Usage:

see [example](https://github.com/abbshr/RocketEngine/tree/v0.5/example)
