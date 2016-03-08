###规范概述
面向前端工程。解决前端工程中性能优化、资源加载（异步、同步、按需、预加载、依赖管理、合并、内嵌）、模块化开发、自动化工具、开发规范、代码部署等问题。


####1. 解决哪些问题
1. 合理的开发流程及开发规范，包括代码规范、模块化组件化规范(分治)等（提高生产力）
2. 一套自动化代码质量检测方案（提高系统可靠性）
3. 一套自动化及高度适应性的项目 发布／部署 方案（提高系统的伸缩性及灵活性）
4. 极致的性能优化，包括减少冗余的接口请求及资源请求、提高缓存命中率等，简言之就是站点的打开及运行速度（更好的用户体验）

####2. 梳理需求
1. 开发规范
2. 模块化开发
3. 组件化开发
4. 组件仓库
5. 性能优化
6. 项目部署
7. 开发流程
8. 开发工具

###方案

[gulp+webpack](https://github.com/havefive/front-end-demo)

### 依赖
1. [nodejs](http://nodejs.org/)
2. [gulp](https://github.com/gulpjs/gulp/)

##[开发规范](https://github.com/havefive/front-end/blob/master/standard.md)

###项目结构
```
项目名称
|-- HISTORY.md
|-- LICENSE
|-- README.md
|-- package.json
|-- dist        # 部署目录
|-- docs        # 文档
|-- fonts       # Icon font，使用 Font Awesome
|-- gulpfile.js # 构建配置文件
|-- webpack.config.js  # webpack配置文件
|-- js          # JS 文件
|-- less        # Less 文件
|-- tools       # 相关工具
|-- tpl         # 模版文件
|-- lib         # 第三方库
|-- widget      # Web 组件
```


###开发流程

![Alt text](https://github.com/havefive/front-end/blob/master/pro.png)
####理念:
1. 一个页面 = 一个模板 + 多个组件
2. 一个组件 = 一份代码 + 一份数据
3. 一个组件开发一次，复用多次
4. 一个页面使用多个组件拼装后，实时预览、快速发布上线

###常用功能

* 文件复制
* 文件压缩
* 图片压缩
* 文件md5
* 文件合并
* webpack打包及es6特性
* 代码内联
* cdn地址
* 合图
* 实时刷新
* 离线包
* bigpipe模版分割
* 自动化测试 // todo


###常见问题

###拓展参考

1. [前端工程化知识要点回顾&思考](https://segmentfault.com/a/1190000003992812) 
2. [腾讯AlloyTeam](http://www.alloyteam.com/)
3. [百度fis3](http://fis.baidu.com/)
4. [大公司里怎样开发和部署前端代码？](https://github.com/fouber/blog/issues/6)











