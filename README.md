myproject/  工程根目录
├── backfont/  这里是后台相关的文件夹，可能有多个
│   
├── frontend/ 在工程根目录下，创建一个web文件夹，前端的开发环境都在这个文件夹内吗，实现前后端分离
│   │
│   ├── .sass-cache/ 这里是sass编译所自动创建的文件夹
│   │
│   ├── src/   这里是开发文件，所有的编写，修改，删除都在这个文件夹下进行
│   │   │───assets
│   │   │     └──styles 
│   │   │         └──sass 全局样式，比如vars，normailize
│   │   │         └──css  这里存放引入无需修改的css文件，例如：font-awesome.min.css
│   │   │     └──images 图片
│   │   └─── view 业务组件 一般与路由挂钩  
│   │   └─── components   功能组件
│   │   └─── styles  这里存放sass文件，例如：index.scss，用于组件的构建
│   │   └─── utils 一些公用API  
│   │   └─── router 路由  
│   │   └─── store Vuex的相关文件 
│   │           └─── actions 
│   │           └─── modules
│   │           └─── index.js
│   │           └─── mutation-type.js
│   │   └─── App.vue 
│   │   └─── index.js  webpack4约定将index.js放在这里
│   │ 
│   ├── index.html 挂载的html文件，webpack4约定将index.html放在这里
│   │
│   ├── dist/ 这里存放webpack打包后的文件
│   │  
│   │
│   ├── node_modules/ 里边放着各种各样你不用关心的文件
│   ├── gulpfile.js   编写gulp任务的文件
├   ├── webpack.config.js
│   ├── package.json  记录各种信息的json
# 介绍
这是一个webpack+gulp+vue+vuex+mock的模板工程。
V 1.0
webpack用来打包文件，编译sass,scss,vue
gulp通过gulp-shell启动webpack。

后续功能等待添加

# 启动方式
```
yarn
gulp
```