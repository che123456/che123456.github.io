
## 浏览器支持
现代浏览器及 IE10

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --- | --- | --- | --- | --- |
| IE10, Edge | last 2 versions | last 2 versions | last 2 versions | last 2 versions |

## 使用
### yarn
```bash
$ yarn install
$ yarn serve
```
### or npm
```
$ npm install
$ npm run serve
```
## 项目目录结构
```
├── public
│   └── favicon.png          # favicon
│   └── index.html           # 入口 HTML
├── src
│   ├── assets               # 本地静态资源
│   ├── components           # 内置通用组件
│   ├── config               # 系统配置
│   ├── layouts              # 通用布局
│   ├── mock                 # 本地 mock 数据
│   ├── pages                # 页面组件和通用模板
│   ├── plugins              # vue 插件
│   ├── router               # 路由配置
│   ├── services             # 数据服务模块
│   ├── store                # vuex 状态管理配置
│   ├── theme                # 主题相关
│   ├── utils                # js 工具
│   ├── App.vue              # 应用入口组件
│   ├── bootstrap.js         # 应用启动引导js
│   └── main.js              # 应用入口js
├── package.json             # package.json
├── README.md                # README.md
└── vue.config.js            # vue 配置文件
```
