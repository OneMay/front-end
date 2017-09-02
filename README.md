## 目录
---
- [front-end](#front-end)
  - [前端综合](#前端综合)
  - [JS相关](#JS相关)
    - [常见编程考验](#常见编程考验)
    - [常用操作](#常用操作)
  - [DOM相关](#DOM相关)
  - [css 相关](#css-相关)
    - [常见编程考验](#常见编程考验)
  - [html 相关](#html-相关)
  - [http,浏览器相关](#http,浏览器相关)
  - [ES6](#ES6)
  - [框架，工具](#框架，工具)
    - [jquery](#jquery)
    - [react ](#react-)
  - [nodejs](#nodejs)
  - [算法题：](#算法题)
  - [面试题](#面试题)
---

# front-end

前端基本功以及面试必备知识。

大家可以把自己想到的常用知识或者面试题补充在下面。每个topic对应一个md文件。可以在现有的文件上进行修改，也可以新建文件保存到对应的文件目录下。

每篇文章的内容都是可以修改的，大家可以增加自己的内容。但是请尽量不要直接复制粘贴博客原文，**最好是自己的思路，整理，总结**。

请把**参考的博客,文章地址**放到每篇文章的`参考文章`后面，方便别人进行扩展阅读。（也可以在引用部分进行标注）

> 注意：请按照下面格式进行文件的添加，readme部分只做目录

如果新增或修改，请在当前页进行标注：

- `+6位时间`表示完成了当前文章（从无到有）

- `!6位时间`表示修改当前文章

例：+170716 表示在2017年7月16日增加了当前文章

## 前端综合

- [web前端性能优化总结](/browser/optimize.md) +170723

- [同源问题与跨域](/about_js/sameorigin.md) +170715

- [cache](/overall/cache.md) +170723

- [cookie](/overall/cookie.md) +170723

- [cookie和session](/overall/cookie.md/#cookie和session) +170723

- [iframe](/overall/iframe.md)

- [通信](/overall/message.md)

- [正则表达式](/overall/regex.md) +170717

- [存储相关](/overall/storage.md) +170723

- [fiddler使用](/overall/fiddler.md)

## JS相关

- [原型(链)](/about_js/prototype.md) +170720 by xiaoch11

- [创建对象和继承](about_js/extend.md) +170717

- [This (call apply bind)](about_js/this.md) +170715 

- [执行环境和作用域链](/about_js/context.md) +170717

- [闭包](/about_js/closure.md) +170721

- [ajax](/about_js/ajax.md) +170721

- [jsonp](about_js/jsonp.md) +170715 

- [数组相关](/about_js/array.md) +170721

- [与和或操作符](/about_js/andor.md) +170723

- [基本类型和隐式转换](/about_js/convert.md) +170723

- [字符串相关](/about_js/string.md) +170721

- [链式调用](/about_js/chain.md) +170723

- [事件](/about_js/event.md) +170720 by xiaoch11

- [事件冒泡和捕获](/about_js/bubble.md) +170723

- [事件委托](/about_js/delegation.md) +170723

- [函数优化（防抖动和节流）](/about_js/optimize.md) + 170806

- [polyfill](/about_js/polyfill.md)

### 常见编程考验

- [如何clone一个对象(深拷贝)](about_js/program.md/#如何实现深浅拷贝) +170715 

- [如何实现数组去重](about_js/program.md/#如何实现数组去重) +170722

- [如何实现sum(1,2),sum(1)(2)](about_js/program.md/#如何实现sum1,2,sum12) +170722

- [如何删除数组中的多个特定元素（必须用splice）](about_js/program.md/#如何删除数组中的多个特定元素必须用splice) +170722

- [求数组中的最大，最小值](about_js/program.md/#求数组中的最大，最小值) +170801

- [如何扁平化数组](about_js/program.md/#如何扁平化数组) +170801

- [如何实现(2).plus(3).minus(1) //4](about_js/program.md/#如何实现2plus3minus1-//4) +170801

- [如何判断一个字符串是回文串](about_js/program.md/#如何判断一个字符串是回文串) +170801

- [如何实现任意进制转换](/about_js/program.md/#如何实现任意进制转换) +170807

- [实现一个lazyman](about_js/lazyman.md) +170715 

### 常用操作

- [遍历DOM节点](about_js/traverse.md) +170807

- [如何实现拖动](about_js/operation.md/#如何实现拖动) +170727

- [如何实现屏幕滚动检测](about_js/operation.md/#如何实现屏幕滚动检测) +170727

## DOM相关

- [屏幕和元素尺寸](/dom/size.md) +170727

- [常用dom操作](dom/dom.md) +17071

- [DOM属性](dom/domattr.md) +17071

## css 相关

- [盒模型](/about_css/box.md) +170726

- [marigin塌陷](/about_css/collapsedmargin.md) +170726

- [层叠](/about_css/cascade.md)

- [css3相关](/about_css/css3.md) +170726

- [包含块,盒,格式化上下文](/about_css/fc.md) +170726

- [flex布局](/about_css/flex.md) +170726

- [流模型](/about_css/flow.md) 

- [hack](/about_css/hack.md) +170806

- [less](/about_css/less.md)

- [sass](/about_css/sass.md)

- [css选择器](/about_css/selector.md) +170720 by xiaoch11

### 常见编程考验

- [基本布局](/about_css/layout.md)  +170718

- [实现水平居中](/about_css/center.md) +170715 

- [实现垂直居中](/about_css/vcenter.md) +170715 

- [实现水平垂直居中](/about_css/hvcenter.md) +170715 

## html 相关

- [doctyp](/about_html/doctype.md)

- [head](/about_html/head.md)

- [语义化标签](/about_html/semantic.md)

- [替换元素](/about_html/replaced.md) +170726

- [常用标签](/about_html/tags.md) +170715 

- [viewpor](/about_html/viewport.md) +170725

## http,浏览器相关

- [浏览器渲染原理和性能优化](/browser/howitworks.md) +170722

- [常见相应代码](/browser/responsecode.md) +170723

- [get和post区别](/browser/getpost.md) +170723

- http头

- 浏览器模式(解释清楚算加分项)

- [安全](/security/xss.md) +170806

- [http性质,头](/browser/http.md) +170807

- [TCP相关](/browser/tcp.md) +170807

## ES6

- [let&const](es6/let&const.md) +170715 

- [变量解构](es6/destructuring.md) +170715 

- [箭头函数](/es6/arrow.md) +170715 

- [class](/es6/class.md)

- [module](/es6/module.md) +170724

- [promise](/es6/promise.md) +170724

- [generator](/es6/generator.md) +170724

## 框架，工具

### vue

- [vue相关](/framework/vue/vue.md) +170725

- [vuex](/framework/vue/vuex.md) +170715 

- [vue-router](/framework/vue/vue_router.md)

### jquery

### angular 

### react 

### webpack

- [webpack基本知识](/framework/webpack.md) +170723

## nodejs

- [nodejs相关](/framework/nodejs/nodejs.md)

- [fs](/framework/nodejs/fs.md)

- [http](/framework/nodejs/http.md)

## 算法题：

- 链表判环

- 翻转链表

- 链表取倒数第n个

- 有序链表合并

- [排序](/algorithm/sort.md)

- 括号的匹配（栈）

- [二叉树](/algorithm/tree.md)

- 背包问题

## 面试题

> 这里可以直接接网址链接，当然还是希望大家发现有新的面试题，但是上面没出现的，补充在上面

- [一道经典的js面试题](/interview/p1.md)

- [windows.onload 和 $(document).ready()区别](/interview/p2.md)

- [你常关注的网站](/interview/p3.md)

- [forEach，map，$.each区别](/interview/p4.md)

- [用setTimeout()方法来模拟setInterval()与setInterval()之间的什么区别？](/interview/p5.md)

- [new Date的兼容性问题](/interview/p6.md)
