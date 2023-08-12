<!--
 * @Author: jincheng
 * @Date: 2023-08-10 15:25:08
 * @FilePath: /vue3-webpack5-admin/README.md
-->

## 目录

├── dist  
| ├── static
| | ├── js
| | ├── main.js
| ├── index.html
├── build
| ├── webpack.base.js # 公共配置
| ├── webpack.dev.js # 开发环境配置
| └── webpack.prod.js # 打包环境配置
├── public
│ └── index.html # html 模板
├── src
| ├── App.vue
│ └── index.ts # vue3 应用入口页面
├── postcss.config # ts 提取postcss-loader配置
├── .browserslistrc # ts 兼容浏览器的清单
├── tsconfig.json # ts 配置
├── babel.config # babel option 配置
└── package.json


安装 webpack5
npm i webpack@5.85.1 webpack-cli@5.1.3 -D

安装 vue
npm i vue@^3.3.4 -S

安装 babel 核心模块和 babel 预设以及 vue-loader @babel/preset-typescript
npm i babel-loader@^9.1.2 @babel/core@^7.22.5 @babel/preset-env@^7.22.5 @babel/preset-typescript@^7.22.5 vue-loader@^17.2.2 -D

添加 html-webpack-plugin 插件
npm i html-webpack-plugin -D

安装 webpack-dev-server
npm i webpack-dev-server webpack-merge -D

打包后的 dist 文件可以在本地借助 node 服务器 serve 打开,全局安装 serve
npm i serve -g

######################################################################

区分变量

安装 cross-env
npm i cross-env -D

安装依赖 style-loader css-loader
npm i style-loader css-loader -D

安装 less
npm i less-loader less -D

处理css3前缀兼容
npm i postcss-loader autoprefixer -D

安装 babel
npm i babel-loader @babel/core @babel/preset-env core-js -D

安装复制静态文件插件
npm i copy-webpack-plugin -D