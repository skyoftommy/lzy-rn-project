# 隆之源 React Native 项目集(开发环境)
> 包含佳音(7038)、佳音企业版(7115)、神州旅游(7085)、聚真、京惠客等项目
--------------
####环境依赖
* [node v10.15.3+](http://nodejs.cn/)
* [expo-cli v2.20.2+](https://expo.io/)
```
  npm install expo-cli --global
```
####开发工具
* [Expo 苹果版](https://apps.apple.com/app/apple-store/id982107779)
* [Expo 安卓版](https://play.google.com/store/apps/details?id=host.exp.exponent&referrer=www)
* [vscode](https://code.visualstudio.com/)
####项目部署
```
  npm install  //安装相关项目依赖
  npm start  //运行项目
```
######新项目(开发环境)
```
  expo init my-new-project  //安装项目文件
  cd my-new-project 
  expo start  //运行项目
```
####项目目录
├── Readme.md                   // help
├── app                         // 应用
├── config                      // 配置
│   ├── default.json
│   ├── dev.json                // 开发环境
│   ├── experiment.json         // 实验
│   ├── index.js                // 配置控制
│   ├── local.json              // 本地
│   ├── production.json         // 生产环境
│   └── test.json               // 测试环境
├── data
├── doc                         // 文档
├── environment
├── gulpfile.js
├── locales
├── logger-service.js           // 启动日志配置
├── node_modules
├── package.json
├── app-service.js              // 启动应用配置
├── static                      // web静态资源加载
│   └── initjson
│       └── config.js         // 提供给前端的配置
├── test
├── test-service.js
└── tools
