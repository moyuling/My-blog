# 前端开发面试题 （题目列表页）

## [目录](question.md)

1. [前言](question.md#preface)
2. [HTML 部分](question.md#html)
3. [CSS  部分](question.md#css)
4. [JavaScript 部分](question.md#js)
5. [其他问题](question.md#other)
6. [优质网站推荐](question.md#web)

## [前言](question.md)

略

## [HTML](question.md)

* Doctype作用? 严格模式与混杂模式如何区分？它们有何意义?
* 行内元素有哪些？块级元素有哪些？ 空\(void\)元素有那些？
* 介绍一下CSS的盒子模型？
* link 和@import 的区别是？
* CSS 选择符有哪些？哪些属性可以继承？优先级算法如何计算？ CSS3新增伪类有那些？
* 如何居中div？如何居中一个浮动元素？
* 浏览器的内核分别是什么?
* html5有哪些新特性、移除了那些元素？如何处理HTML5新标签的浏览器兼容问题？如何区分 HTML 和 HTML5？
* 语义化的理解？
* HTML5的离线储存？
* \(写\)描述一段语义的html代码吧。
* iframe有那些缺点？
* Label的作用是什么？是怎么用的？（加 for）
* HTML5的form如何关闭自动完成功能？给不想要提示的input是设置autocomplete=off即可
* 请描述一下 cookies，sessionStorage 和 localStorage 的区别？
* 如何实现浏览器内多个标签页之间的通信? \(阿里\)
* webSocket如何兼容低浏览器？\(阿里\)
* 页面可见性（Page Visibility）API 可以有哪些用途？
* 你是怎么切图的？

## [CSS](question.md)

* 列出display的值，说明他们的作用。position的值， relative和absolute定位原点是？
* CSS3有哪些新特性？
* 用纯 CSS 创建一个三角形
* 一个满屏 品 字布局 如何设计?
* 经常遇到的浏览器的兼容性有哪些？原因，解决方法是什么，常用hack的技巧 ？
* 为什么要初始化CSS样式。
* absolute的containing block计算方式跟正常流有什么不同？
* CSS里的visibility属性有个collapse属性值是干嘛用的？在不同浏览器下以后什么区别？
* position跟display、margin collapse、overflow、float这些特性相互叠加后会怎么样？
* 对BFC规范的理解？
* css定义的权重？
* 解释下浮动和它的工作原理？清除浮动的技巧
* 用过媒体查询，针对移动端的布局吗？
* 使用 CSS 预处理器吗？喜欢那个？
* CSS 优化、提高性能的方法有哪些？
* 浏览器是怎样解析CSS选择器的？
* 这个CSS它是如何工作的？（ .mod-nav h3 span {font-size: 16px;} ）
* 在网页中的应该使用奇数还是偶数的字体？为什么呢？
* margin和padding分别适合什么场景使用？
* 元素竖向的百分比设定是相对于容器的宽度吗？
* 全屏滚动的原理是什么？用到了CSS的那些属性？
* ::before 和 :after中双冒号和单冒号 有什么区别？解释一下这2个伪元素。
* 你对line-height是如何理解的？
* 设置元素浮动后，改元素的display值是多少？（自动变成display:block）
* 怎么让Chrome支持小于12px 的文字？
* 让页面里的字体变清晰，变细用CSS怎么做？（-webkit-font-smoothing: antialiased;）
* font-style属性 可以让它赋值为“oblique” oblique是什么意思？
* position:fixed;在android下无效怎么处理？
* 如果需要手动写动画，你认为最小时间间隔是多久，为什么？（阿里）
* display:inline-block 什么时候会显示间隙？\(携程\)

## [JavaScript](question.md)

* 用原生JS的写过东西吗？
* JavaScript原型，原型链 ? 有什么特点？
* JavaScript 有几种类型值？（堆：原始值和 栈：引用值），你能画一下他们的内存图吗？
* eval是做什么的？
* null，undefined 的区别？
* 写一个通用的事件侦听器函数。
* Node.js的适用场景？
* 介绍js的基本数据类型。
* Javascript如何实现继承？
* \["1", "2", "3"\].map\(parseInt\) 答案是多少？
* 如何创建一个对象? （画出此对象的内存图）
* 谈谈This对象的理解。
* 事件、IE与火狐的事件机制有什么区别？ 如何阻止冒泡？
* 什么是闭包（closure），为什么要用它？
* "use strict";是什么意思 ? 使用它的好处和坏处分别是什么？
* 如何判断一个对象是否属于某个类？
* new操作符具体干了什么呢?
* Javascript中，有一个函数，执行时对象查找时，永远不会去查找原型，这个函数是？
* JSON 的了解？
* \[\].forEach.call\($$\("_"\),function\(a\){ a.style.outline="1px solid \#"+\(~~\(Math.random\(\)_\(1&lt;&lt;24\)\)\).toString\(16\) }\) 能解释一下这段代码的意思吗？
* js延迟加载的方式有哪些？
* ajax 是什么?
* 同步和异步的区别?
* 如何解决跨域问题?
* 模块化怎么做？
* AMD（Modules/Asynchronous-Definition）、CMD（Common Module Definition）规范区别？
* 异步加载的方式有哪些？
* .call\(\) 和 .apply\(\) 的区别？
* Jquery与jQuery UI 有啥区别？
* JQuery的源码看过吗？能不能简单说一下它的实现原理？
* jquery 中如何将数组转化为json字符串，然后再转化回来？
* 针对 jQuery 的优化方法？
* JavaScript中的作用域与变量声明提升？
* 如何编写高性能的Javascript？
* 那些操作会造成内存泄漏？
* JQuery一个对象可以同时绑定多个事件，这是如何实现的？
* 写一个无刷新的网站，并且能在浏览器前进、后退时正确响应怎么实现？
* 如何判断当前脚本运行在浏览器还是node环境中？（阿里）
* canvas的默认大小是多少？
* 移动端最小触控区域是多大？
* jQuery 的 slideUp动画 ，如果目标元素是被外部事件驱动, 当鼠标快速地连续触发外部元素事件, 动画会滞后的反复执行，该如何处理呢?
* 移动端的点击事件的有延迟，时间是多久，为什么会有？ 怎么解决？（click 有 300ms 延迟,为了实现safari的双击事件的设计）
* Zepto的点透问题如何解决？

## [其他问题](question.md)

* 你遇到过比较难的技术问题是？你是如何解决的？
* 常使用的库有哪些？常用的前端开发工具？开发过什么应用或组件？
* 页面重构怎么操作？
* 列举IE 与其他浏览器不一样的特性？
* 99%的网站都需要被重构是那本书上写的？
* 什么叫优雅降级和渐进增强？
* WEB应用从服务器主动推送Data到客户端有那些方式？
* 对Node的优点和缺点提出了自己的看法？
* 你有哪些性能优化的方法？
* http状态码有那些？分别代表是什么意思？
* 一个页面从输入 URL 到页面加载显示完成，这个过程中都发生了什么？（流程说的越详细越好）
* 除了前端以外还了解什么其它技术么？你最最厉害的技能是什么？
* 你常用的开发工具是什么，为什么？
* 对前端界面工程师这个职位是怎么样理解的？它的前景会怎么样？
* 你怎么看待Web App 、hybrid App、Native App？
* 你移动端前端开发的理解？（和 Web 前端开发的主要区别是什么？）
* 加班的看法？
* 平时如何管理你的项目？
* git如何删除错误提交的文件？
* 如何设计突发大规模并发架构？
* 说说最近最流行的一些东西吧？平时常去哪些网站？
* 移动端（Android IOS）怎么做好用户体验?
* 你在现在的团队处于什么样的角色，起到了什么明显的作用？
* 你认为怎样才是全端工程师（Full Stack developer）？
* 介绍一个你最得意的作品吧？
* 你有自己的技术博客吗，常去那些技术博客？
* 最近在学什么？能谈谈你未来3，5年给自己的规划吗？

## 有趣的问题

* .A、B两人分别在两座岛上。B生病了，A有B所需要的药。C有一艘小船和一个可以上锁的箱子。C愿意在A和B之间运东西，但东西只能放在箱子里。只要箱子没被上锁，C都会偷走箱子里的东西，不管箱子里有什么。如果A和B各自有一把锁和只能开自己那把锁的钥匙，A应该如何把东西安全递交给B？

  ```text
  答案：A把药放进箱子，用自己的锁把箱子锁上。B拿到箱子后，再在箱子上加一把自己的锁。
  ```

  箱子运回A后，A取下自己的锁。箱子再运到B手中时，B取下自己的锁，获得药物。

## [优质网站推荐](question.md)

1. 极客标签：     [http://www.gbtags.com/](http://www.gbtags.com/)
2. 码农周刊：     [http://weekly.manong.io/issues/](http://weekly.manong.io/issues/)
3. 前端周刊：     [http://www.feweekly.com/issues](http://www.feweekly.com/issues)
4. 极客头条：   [http://geek.csdn.net/](http://geek.csdn.net/)
5. Startup News：[http://news.dbanotes.net/](http://news.dbanotes.net/)
6. Hacker News： [https://news.ycombinator.com/news](https://news.ycombinator.com/news)
7. InfoQ：        [http://www.infoq.com/](http://www.infoq.com/)
8. w3cplus：    [http://www.w3cplus.com/](http://www.w3cplus.com/)
9. Stack Overflow： [http://stackoverflow.com/](http://stackoverflow.com/)

### last updated:  2015-03-25

爱机车、爱骑行、爱旅行、爱摄影、爱阅读的理想青年，前端开发攻城师。

我的微博：[http://weibo.com/920802999](http://weibo.com/920802999)

