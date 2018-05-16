
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

# 项目结构

├─dist 这里存放webpack打包后的文件
├─docs 存放文档
├─index.html 挂载的html文件，webpack4约定将index.html放在这里
├─node_modules 里边放着各种各样你不用关心的文件
├─gulpfile.js   编写gulp任务的文件
├─package.json  记录各种信息的json
├─mock mocksever
│  └─server
└─src   这里是开发文件，所有的编写，修改，删除都在这个文件夹下进行
    ├─assets
    │  ├─images
    │  └─styles
    │      ├─css  这里存放引入无需修改的css文件，例如：font-awesome.min.css
    │      └─sass 全局样式，比如vars，normailize
    ├─components 功能组件
    ├─router 
    ├─store  Vuex的相关文件 
    │  ├─actions
    │  └─modules
    ├─styles 这里存放sass文件，例如：index.scss，用于组件的构建
    ├─utils 一些公用API
    │─view 业务组件 一般与路由挂钩
    ├─App.vue 
    └─index.js  webpack4约定将index.js放在这里   
