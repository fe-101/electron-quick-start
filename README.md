electron 快速入门 ![](https://img.shields.io/npm/l/whistle.svg?style=flat-square) 
===

> 使用 JavaScript, HTML 和 CSS 构建跨平台的桌面应用
> —— [electronjs.org](https://electronjs.org/)

<br>

## 前言
基于 [electron-quick-start](https://github.com/electron/electron-quick-start) 翻译、修改并添加 [electron-builder](https://www.electron.build/) 打包工具

<br>

## 使用
下载安装
```
$ git clone git@github.com:haloislet/electron-quick-start.git 
$ cd electron-quick-start
$ npm i
```

启动开发环境
```
$ npm run dev 
```

构建跨平台应用程序
```
$ npm run pack:win 
$ npm run pack:mac
$ npm run pack:linux 
$ npm run pack 
```
构建生成的应用程序位于项目的 dist 目录中。

<br>

## 说明
- windows 下制作不了 mac 安装包。
- windows 下制作 linux 安装包使用的是远程制作，需要使用到 node 的 http2 模块，要求 node>= v8.4.0。
- 因网络问题无法下载相关包，可在 [releases](https://github.com/haloislet/electron-quick-start/releases) 中下载

<br>

## 许可证

The MIT License (MIT)
