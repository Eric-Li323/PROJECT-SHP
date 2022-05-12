1: vue-cli脚手架初始化项目
前提：node + webpack + 淘宝镜像

脚手架目录介绍
node_modules文件夹：存放项目依赖

public文件夹： 一般放置一些静态资源（图片），需要注意，放在public文件夹中的静态资源，webpack进行打包，会原封不动打包到dist文件夹中。

src文件夹（程序员源代码文件夹）：
    assets文件夹：一般也是放置静态资源（一般放置多个组件共用的静态资源），需要注意，放置在assets文件夹里面静态资源，在webpack打包的时候，webpack会把静态资源当做一个模块，打包到JS文件里面。

    components文件夹：一般放置的是非路由组件（或者全局组件）

    App.vue: 唯一的根组件，Vue当中的组件（.vue）
    main.js: 程序入口文件，也是整个程序当中最先执行的文件

.gitignore: git上传时忽略的文件

babel.config.js: 配置文件（babel相关，可理解为一个翻译官，把es6的语法翻译为es5语法，让兼容性更好）

package.json文件：类似于身份证，记录了本项目的信息，如：项目名称，项目依赖有哪些，项目怎么运行

package-lock.json文件：缓存性文件 （可删除）

README.md：文档说明文件