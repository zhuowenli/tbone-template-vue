# tbone-template-vue

使用 vue 多端开发(小程序和Web)，基于 [tbone](https://github.com/zhuowenli/tbone) 的 element 和 render。

## 特性

* 一键接入，立即使用
* 支持更完整的 vue 语法及特性
* webpack、es6、babel、hot reload、cli、vue-router、vuex，你想要的都有

## 构建

* Web 端：构建完成会生成 dist/web 目录

```bash
npm run build
```

* 小程序端：构建完成会生成 dist/mp 目录

```bash
npm run mp
```

## 目录说明

```js
├─ build
│  ├─ miniapp.config.js      // mp-webpack-plugin 配置
│  ├─ webpack.mp.config.js   // 小程序端构建配置
│  └─ webpack.config.js      // Web 端构建生产环境配置
├─ dist
│  ├─ mp                     // 小程序端目标代码目录，使用微信开发者工具打开，用于生产环境
│  └─ web                    // web 端编译出的文件，用于生产环境
├─ src
│  ├─ component              // 通用组件
│  ├─ index                  // home 页面
│  ├─ App.vue                // 入口主视图
│  ├─ main.mp.js             // 小程序端入口文件
│  └─ main.js                // Web 端入口文件
└─ index.html                // Web 端入口模板
```

## License

MIT
