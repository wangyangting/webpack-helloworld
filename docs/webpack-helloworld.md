# Webpack HelloWorld

author: [那伊抹微笑](https://github.com/wangyangting)  
github: http://github.com/wangyangting  
date: 2018-09-13 17:03:21

## 步骤
1. npm init  // 初始化， 一路回车即可。
2. npm install --save-dev webpack  // 安装 webpack 至该项目中，不要使用全局安装的方式。
3. npm install --save-dev webpack-cli  // webpack4 需要，不然后面执行 `node_modules\.bin\webpack --mode development` 时会报错。
4. 新建 public/index.html
5. 新建 app/index.js app/hello.js  // index.js 引入了 hello.js
6. node_modules\.bin\webpack --mode development  // 执行打包

## 参考
<https://www.cnblogs.com/Immortal-brother/p/8695179.html>  
<https://www.cnblogs.com/pomelott/p/8977092.html>