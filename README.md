# 隆之源 React Native 项目集(开发环境)
> 包含佳音(7038)、佳音企业版(7115)、神州旅游(7085)、聚真、京惠客等项目
--------------
#### 环境依赖
* [node v10.15.3+](http://nodejs.cn/)
* [expo-cli v2.20.2+](https://expo.io/)
```
  npm install expo-cli --global
```
#### 开发工具
* [Expo 苹果版](https://apps.apple.com/app/apple-store/id982107779)
* [Expo 安卓版](https://play.google.com/store/apps/details?id=host.exp.exponent&referrer=www)
* [vscode](https://code.visualstudio.com/)
#### 参考文档
* [React Native 中文文档](https://reactnative.cn/docs/getting-started/)
#### 项目部署
```
  npm install  //安装相关项目依赖
  npm start  //运行项目
```
###### 新项目部署（开发环境）
```
  expo init my-new-project  //安装项目文件
  cd my-new-project 
  expo start  //运行项目
```
#### 项目目录
```
├── Readme.md                          // help
├── app                                // 应用
│   ├── actions                        // 
│   ├── components                     // 组件
│   ├── libs                           // 第三方包
│   ├── module                         // 模块
│   ├── router                         // 路由
│   │   ├── router.js                  // 路由 - 京惠客
│   │   ├── router-fanli.js            // 路由 - 分销（佳音）
│   │   ├── router-fanli-supplier.js   // 路由 - 分销企业版（佳音企业版）
│   │   ├── router-oem.js              // 路由 - 分销oem
│   │   ├── router-travel.js           // 路由 - 神州旅游
│   │   └── router-v5.js               // 路由 - v5商城
│   ├── style                          // 样式
│   ├── view                           // 页面 - 京惠客
│   ├── view_fanli                     // 页面 - 分销（佳音）
│   ├── view_fanli_supplier            // 页面 - 分销企业版（佳音企业版）
│   ├── view_oem                       // 页面 - 分销oem
│   ├── view_travel                    // 页面 - 神州旅游
│   ├── view_v5                        // 页面 - v5商城
│   └── setup.js                       // 入口文件（按需加载路由）
├── assets                             // 静态文件
├── node_modules                       // node组件包
├── App.js                             // 应用注册文件
└── package.json                       // 应用组件包文件
```

###### 项目引用的第三方组件（package.json）
* [axios 网络请求组件](https://www.npmjs.com/package/axios)
* [crypto-js 加密组件](https://www.npmjs.com/package/crypto-js)
* [js-base64 base64加密组件](https://www.npmjs.com/package/js-base64)
* [node-emoji emoji组件](https://www.npmjs.com/package/node-emoji)
* [node-emoji emoji组件](https://www.npmjs.com/package/node-emoji)
* [react-native-drawer 抽屉组件](https://www.npmjs.com/package/react-native-drawer)
* [react-native-easy-toast toast组件](https://www.npmjs.com/package/react-native-easy-toast)
* [react-native-ezswiper 轮播图组件](https://www.npmjs.com/package/react-native-ezswiper)
* [react-native-image-zoom-viewer 图片预览组件](https://www.npmjs.com/package/react-native-image-zoom-viewer)
* [react-native-iphone-x-helper iphoneX识别组件](https://www.npmjs.com/package/react-native-iphone-x-helper)
* [react-navigation 页面跳转组件](https://www.npmjs.com/package/react-navigation)
* [react-native-qrcode 二维码生成组件](https://www.npmjs.com/package/react-native-qrcode)
* [react-native-qrcode-svg 二维码生成组件](https://www.npmjs.com/package/react-native-qrcode-svg)
* [react-native-scrollable-tab-view tab页面滑动组件](https://www.npmjs.com/package/react-native-scrollable-tab-view)
* [react-native-storage 缓存组件](https://www.npmjs.com/package/react-native-storage)
* [react-native-swipe-list-view](https://www.npmjs.com/package/react-native-swipe-list-view)
* [react-native-swiper 轮播图组件](https://www.npmjs.com/package/react-native-swiper)
* [rn-fetch-blob](https://www.npmjs.com/package/rn-fetch-blob)
* [underscore](https://www.npmjs.com/package/underscore)
