# Webpack 3.X 前端工程化             

我的目的是这个做一个最强大的webpack教程手册，供以后工作中翻阅查询                

目录：             
- [一、由浅入深Webpack](./01、由浅入深Webpack/README.md#class1)
    - [01、最基本的使用webpack](./01、由浅入深Webpack/README.md#class1-item01)
    - [02、打包js](./01、由浅入深Webpack/README.md#class1-item02)
    - [03、编译ES6/7](./01、由浅入深Webpack/README.md#class1-item03)
    - [04、编译打包TS](./01、由浅入深Webpack/README.md#class1-item04)
    - [05、提取公用代码](./01、由浅入深Webpack/README.md#class1-item05)
    - [06、代码分割和懒加载](./01、由浅入深Webpack/README.md#class1-item06)                 
    - [07、处理css: style-loader](./01、由浅入深Webpack/README.md#class1-item07)
    - [08、处理css: css-loader](./01、由浅入深Webpack/README.md#class1-item08)
    - [09、配置less/sass](./01、由浅入深Webpack/README.md#class1-item09)
    - [10、提取css](./01、由浅入深Webpack/README.md#class1-item10)
    - [11、postCss-in-webpack](./01、由浅入深Webpack/README.md#class1-item11)
    - [12、Tree-shaking](./01、由浅入深Webpack/README.md#class1-item12)
    
- [二、由浅入深Webpack - 进阶](./02、由浅入深Webpack-进阶/README.md#class2)
    - [01、文件处理 - 图片处理](./02、由浅入深Webpack-进阶/README.md#class2-item01)
    - [02、文件处理-字体处理](./02、由浅入深Webpack-进阶/README.md#class2-item02)
    - [03、文件处理-处理第三方JS库](./02、由浅入深Webpack-进阶/README.md#class2-item03)
    - [04、html-in-webpack-生成html](./02、由浅入深Webpack-进阶/README.md#class2-item04)
    - [05、html中引入图片](./02、由浅入深Webpack-进阶/README.md#class2-item05)
    - [06、配合优化](./02、由浅入深Webpack-进阶/README.md#class2-item06)

- [三、webpack构建本地开发环境](./03、webpack构建本地开发环境/README.md#class3)
    - [01、webpack_watch_mode](./03、webpack构建本地开发环境/README.md#class3-item01)
    - [02、webpack_dev_server](./03、webpack构建本地开发环境/README.md#class3-item02)
    - [03、代理远程接口](./03、webpack构建本地开发环境/README.md#class3-item03)
    - [04、模块热更新](./03、webpack构建本地开发环境/README.md#class3-item04)
    - [05、开启调试模式Source Map](./03、webpack构建本地开发环境/README.md#class3-item05)
    - [06、设置EsLint检查代码格式](./03、webpack构建本地开发环境/README.md#class3-item06)
    - [07、区分开发环境和生产环境](./03、webpack构建本地开发环境/README.md#class3-item07)
    - [08、使用middleware搭建开发环境](./03、webpack构建本地开发环境/README.md#class3-item08)
    
- [四、webpack实战场景](./04、webpack实战场景/README.md#class4)
    - [01、打包结果分析](./04、webpack实战场景/README.md#class4-item01)
    - [02、打包速度优化](./04、webpack实战场景/README.md#class4-item02)
    - [03、长缓存优化](./04、webpack实战场景/README.md#class4-item03)
    - [04、webpack多页面应用](./04、webpack实战场景/README.md#class4-item04)


- webpack优化问题
    - [图片处理](./05、webpack优化问题/01、图片处理.md)
    - [webpack 中那些最易混淆的 5 个知识点](https://juejin.im/post/5cede821f265da1bbd4b5630)
    - [pre-commit限制提交检测](./05、webpack优化问题/02、pre-commit限制提交检测.md)
    - [prettier和lint检测](./05、webpack优化问题/03、prettier和lint检测.md)


- 实战案例
    - [从零搭建React全家桶框架教程](https://github.com/brickspert/blog/issues/1)
    - [配置一套属于自己的React项目的webpack配置](https://github.com/heyushuo/Webpack-React)
    - [从零开始配置TypeScript + React + React-Router + Redux + Webpack开发环境](https://www.cnblogs.com/baqiphp/p/7647912.html)
    - [Demos && Courses for Webpack 4](https://github.com/dongyuanxin/webpack-demos)
    - [tsx+webpack4](https://github.com/cli-template-build/tsx-app)
    - [一步步从零开始用 webpack 搭建一个大型项目 - *** ](https://juejin.im/post/5de06aa851882572d672c1ad)
    - [webpack 最佳配置指北](https://juejin.im/post/5e0e1153e51d45414b74de65?utm_source=gold_browser_extension)

- 其他补充知识点
    - [webpack4系列中文教程和配套代码](https://github.com/dongyuanxin/webpack-demos)
    - [学习webpack4.0的最新配置语法和新特性](https://github.com/wlx200510/webpack4.x-learn)
    - [Webpack-dev-server的proxy用法](https://www.jianshu.com/p/f489e7764cb8)
    - [babel-polyfill的几种使用方法](https://blog.csdn.net/weixin_41224029/article/details/90213067)
    - [Webpack 4 Tree Shaking 终极优化指南](https://juejin.im/post/5dcec27d5188254b0147e619#heading-0)

    
- webpack插件和loader开发
    - [npm link的使用](https://www.jianshu.com/p/aaa7db89a5b2)
    - [巧用 webpack loader 实现项目的定制化](https://www.jqhtml.com/44792.html)
    - [深入Webpack-编写Loader](https://segmentfault.com/a/1190000012718374)


## 遗留问题待解决              

1、postcss 的独立配置文件怎么写                            
2、打包后的js和css 如何自动插入到页面中去                    
3、多页应用程序打包方式                
4、在任意位置的图片地址访问问题处理办法                    



