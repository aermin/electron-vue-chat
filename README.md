
#### 概述

使用electron-vue这个脚手架，快速地将我原先[web项目的代码](https://github.com/aermin/vue-chat)迁移过来复用。

#### Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:9080
npm run dev

# build electron application for production
npm run build


```

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue)@[7c4e3e9](https://github.com/SimulatedGREG/electron-vue/tree/7c4e3e90a772bd4c27d2dd4790f61f09bae0fcef) using [vue-cli](https://github.com/vuejs/vue-cli). Documentation about the original structure can be found [here](https://simulatedgreg.gitbooks.io/electron-vue/content/index.html).

#### 项目展示

简单展示其中一个页面，具体详情请看https://github.com/aermin/vue-chat

![a03eb0555404b38feb7a2dbca15c7db1 1](https://user-images.githubusercontent.com/24861316/41197429-d8272120-6c90-11e8-9874-f1f9ff7ca1ea.jpg)



#### 目录

```
├── LICENSE
├── README.md
├── appveyor.yml
├── build
│   └── icons
├── dist
│   ├── electron
│   └── web
├── node_modules
├── package-lock.json
├── package.json
├── src 
│   ├── index.ejs
│   ├── main  //主进程
│   │   ├── index.dev.js
│   │   └── index.js
│   └── renderer  //渲染进程
│       ├── App.vue
│       ├── assets
│       ├── components
│       ├── main.js
│       ├── pages
│       ├── router
│       ├── store
│       └── utils
├── static
└── yarn.lock
```

#### 注意 

本项目只有前端代码，使用我线上的后端接口，接口仅供学习测试使用（弱鸡学生机请勿恶搞😂）

[后端代码传送门](https://github.com/aermin/vue-chat/tree/master/server)


#### 感谢第三方材料

[electron-vue文档](https://simulatedgreg.gitbooks.io/electron-vue/content/cn/)
