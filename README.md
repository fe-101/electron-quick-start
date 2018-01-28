electron 快速入门 ![](https://img.shields.io/github/license/mashape/apistatus.svg) 
===

> 使用 JavaScript, HTML 和 CSS 构建跨平台的桌面应用
> —— [electronjs.org](https://electronjs.org/)

<br>

## 前言
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

构建款平台应用程序
```
$ npm run build
```
构建生成的应用程序位于项目的 dist 目录中。
构建过程中需要下载各平台的 electron 构建包。如下载速度较慢，可前往[ electron github 仓库 ](https://github.com/electron/electron/releases)下载最新的正式版构建包。下载完之后放到`~/Library/Caches/electron`目录下再执行`npm run build`

<br>

## 许可证

The MIT License (MIT)