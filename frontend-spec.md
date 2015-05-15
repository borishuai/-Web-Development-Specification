## Coding Style
1. [JavaScript](http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml)
2. [HTML/CSS](http://google-styleguide.googlecode.com/svn/trunk/htmlcssguide.xml)

## 模块化开发
1. 使用RequireJS进行模块化开发
2. 部署的代码需要用r.js进行处理
3. 原则上使用[MVCR](http://git.augmentum.com.cn/frontend/mvcr)作为整个模块化开发的基础

## 浏览器支持
1. IE8+, Chrome, Firefox, Safari完整支持
2. IE6, IE7作有限的支持，即有些特殊效果可以不支持，但必须不影响用户功能的使用

## 前端自动化
1. 使用GruntJS作为前端自动化工具
2. 所有CSS和JS在提交之前都需要运行CSSLint和JSHint进行语法检查
3. 最终部署的代码需要运行GruntJS进行压缩合并等处理

## JS单元测试
1. JS代码需要逐步引入单元测试
2. 使用Jasmine/QUnit进行测试
3. 基于PhantomJS平台进行测试

## CSS开发
1. 基于BootStrap3进行开发
2. 原则上支持响应式布局
3. 代码要满足[CSS架构](http://blog.csdn.net/borishuai/article/details/9671619)的要求
4. 类的命名请参考：[HTML语义和前端架构](http://blog.csdn.net/borishuai/article/details/9671721)
