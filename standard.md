
###HTML规范
1. 参考[AmazeUI](http://amazeui.org/getting-started/html-css-guide)
2. 常见规则
   
   ####使用UTF-8 编码
   
```
 <meta charset="UTF-8">
 
```
   * 省略外链资源 URL 协议部分
	
```
	//推荐写法：
	<script src="//www.google.com/js/gweb/analytics/autotrack.js"></script>
	或
	.example {
        background: url(//www.google.com/images/example);
    }
	
```
   * 一律使用小写字母

```
<img src="google.png" alt="Google">

```   
   

###CSS规范

1. 不要使用 @import(替代办法：用postcss处理成一个文件)
2. 命名规则
3. 使用 rem 作为字号、长度单位,精准定位的，仍然使用 px
 
######ID、Class 使用语义化、通用的命名方式。
 * 只允许使用的小写字母、连字符、数字；
 * 应该从 ID 和 Class 的名字上就能看出这元素是干嘛用的（角色、功能、状态），而不是表象（颜色、位置等）或模糊不清的命名；
 * 表明、反映元素作用的名字易于理解，且后期修改的可能性小；
 * 对与同级元素相比没有特殊的意义的元素使用通用的命名；
使用功能性或通用的名字可以减少不必要的文件修改。
 * 使用连字符 - 作为 ID、Class 名称界定符


###JS规范
######1. 使用 JSHint 和 JSCS 控制代码质量
######2. [Nodejs单元测试Mocha](https://segmentfault.com/a/1190000002921481)

###组件规范

######1. Web 组件基于基础库（CSS / JS）开发，在基础库已有样式、功能的基础上做更多扩展。

######2. 目录结构
```
组件目录结构
|-- HISTORY.md
|-- LICENSE
|-- README.md
|-- package.json
|-- demo        # 实例
|-- docs        # 文档
|-- css         # css 文件
|-- js          # JS 文件
|-- less        # Less 文件
|-- lib         # 第三方库
```
###### 3. 示例图

![Alt text](https://github.com/havefive/front-end/blob/master/page.png)
