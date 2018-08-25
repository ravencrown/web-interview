# 前端面试题总结

以下是一些身边的同事，包括自己在找工作的时候，遇到的面试题，希望对你有帮组。面试题基本来自大厂 - 百度、阿里、腾讯、美团、滴滴、头条、58 等等，很有参考借鉴的价值


## JavaScript

### 1. AMD和commonjs的区别
### 2. 立即执行函数 解决方法和引发原因
### 3. jquery和zepto的区别，获取元素方式的区别
### 4. es6的箭头函数，基础知识
### 5. 事件代理
### 6. 事件的冒泡，捕获  — 这个可以防止什么问题
### 7. 变量提升
### 8. 变量范围Scope，在严格模式和非严格模式的区别
### 9. 异步函数封装
### 10. ES6: 箭头函数好处等等
### 11. promise
### 12. JS垃圾回收机制
### 13. 短路运算符
### 14. this和apply的应用
### 15. typeof
### 16. 比较和相等
### 17. zepto 点击穿透问题
### 18. sort 排序原理
### 19. indexof 什么时候可以用于数组
### 20. jsonp 优缺点？ 事件委托怎么取索引
### 21. webkit实现原理 和 V8 哪个效率高？
### 22. null/undefined 的区别
### 23. 如何判断  NaN
### 24. nodejs 同步异步读取文件
### 25. eventLoop
### 26. ES5/ES6 的继承除了写法以外还有什么区别
### 27. JS 渲染机制
### 28. 简单介绍下 JS 的原型和原型链
### 29. 如何判断 JS 变量的一个类型（至少三种方式）
### 30. for/in、Object.keys 和 Object.getOwnPropertyNames 对属性遍历有什么区别？
### 31. 在子 iframe 中调用外层页面的接口，传入一个对象，外层页面如何判断该对象是否为数组？
### 32. 请简要描述 webview 中通过 js bridge 和 native 通信的技术实现
### 33. 如何判断一个对象是否为数组
### 34. <script> 标签的 defer 和 asnyc 属性的作用以及二者的区别？
### 35. Object.prototype.toString.call() 和 instanceOf 和 Array.isArray() 区别好坏
### 36. typeof 可以判断的类型
### 37. ASCII 英文转码
### 38. ES6 都有什么 iterater 遍历器
### 38. 松散类型的数组
### 39. JS严格模式和正常模式
### 40. 闭包应用
### 41. 变量作用域提升
### 42. 移动端tap点击事件和click的区别
### 43. jquery的链式操作
### 44. jquery的源码
### 45. JS单线程还是多线程，如何显示异步操作
### 46. JavaScript数组的函数 map/forEach/reduce/filter
### 47. JS块级作用域、变量提升
### 48. ES6 语法及熟悉
### 49. 说下 jQuery/Zepto 中的 on 方法有哪些参数，分别代表什么意思？
### 50. 将字符串转换成 JSON 对象的方法和将 JSON 对象转换成 字符串的方法？
### 51. 移动端的点击事件的延时，时间是多少，为什么有？ 怎么解决这个延时？
### 52. JS 哪些操作会造成内存泄露
### 53. JS 哪些操作会引起页面重绘
### 54. console.log([1<2<3>, 3>2>1]),输出是多少
### 55. 发布订阅设计模式
### 56. AJAX 原生写法
### 57. 防抖，节流
### 58. 闭包，作用域
### 59. JS 原型链
### 60. ES5 Bind的实现
### 61. Event Loop 
### 62. bind的实现
### 63. polyfill
### 64. 兼容各种浏览器版本的事件绑定
### 65. typescript 遇到过什么坑

## 网络安全存储

### 1. Get/POST的区别
### 2. Http状态码，Http2是什么
### 3. Http请求的整个过程
### 4. http 缓存配置怎么设置
### 5. 操作系统线程怎么操作
### 6. 常见的浏览器端的存储技术有哪些， 以及它们的优缺点和使用场景？
### 7. 最常见的跨域技术方案有哪些？其中 JSONP的原理和缺点是什么？
### 8. 在HTTP响应 Header 中，set-cookie 选项有哪些，分别代表什么含义？
### 9. 何为跨域？ 跨域请求数据有几种方式？图片/脚本 等资源有什么跨域问题。如何解决？跨域请求时如何携带 cookie
### 10. 简要描述 HTTPS 的安全机制，以及在 web 服务工程实践中需要注意的问题。描述 http2 和 https 的关系
### 11. 什么是点击劫持？如何防范？
### 12. 什么是 CSRF, 怎么造成的， 有什么防御方法？
### 13. cookie 和 Session 有什么区别？
### 14. 请简述如何在 HTML 中开启和关闭 DNS 预读取?
### 15. DNS 回源策略
### 16. https 实现原理
### 17. 浏览器从输入 URL 到页面加载发生了什么
### 18. 怎么理解离线存储？大致描述一下怎么使用？
### 19. XSS 怎么解决？
### 20. CSRF cookie 问题？ 没有笔试题
### 21. CDN 原理


## CSS 

### 1. 弹性布局 flex的详细用法
### 2. rem和em的区别
### 3. BFC深入
### 4. 如何去除浮动？请写出最保险最常用的。
### 5. 实现三列布局，side1 和 side2 左右两列宽度固定（200px）,main 中间宽度自适应（不能用弹性盒）
### 6. 实现固定宽度（200 x 400） 的弹层，在窗口中（上下左右）居中显示。
### 7. CSS 属性 box-sizing 的值有哪些？ 分别有什么含义？
### 8. rem 是什么含义？如何实现页面宽度适配为375 rem 的设计稿？
### 9. 使用 CSS3 设计一个立起的原型，并围绕自身中轴线做 360° 持续旋转
### 10. 用 CSS 分别实现单行截断和多行截断字符串，最后以...为结尾
### 11. CSS选择器优先级怎么算的？
### 12. rem的使用，还有其他哪些适配的技术：meta device-width
### 13. 设备像素比
### 14. BFC
### 15. 请根据下面的 HTML 和 CSS 代码，画出布局示意图,宽度不必精确到像素，示意即可。

```html
<div id="page">
    <div class="main">
        <div class="sub"></div>
    </div>
    <div class="nav"></div>
</div>

<style type="text/css">
    #page { width: 520px; }
    .nav { width: 200px; float: right }
    .main { width:200px; float: left; padding-left: 110px; }
    .sub { width: 100px; float: left; margin: 10px 0 10px -100px; }
    .main { border: 1px solid #000; }
    .nav, .sub{ border: 1px; dashed #000; height: 300px }
    .sub { height: 280px }
</style>
```

### 16. 请列举你所知道的清楚浮动的方式。
### 17. 请用 CSS 定义 <p> 标签, 要求实现以下效果：字体颜色在 IE6 下为黑色（#000000）；IE7下为红色（#ff0000）; 而其他浏览器下为绿色（#00ff00）
### 18. 请写出几种常用的行内元素和块级元素
### 19. 几种常见可以继承的 CSS 样式
### 20. position 属性有哪些值，分别代表什么意思？ 使用与什么场景？
### 21. style 标签写在 body 后和 body 前有什么区别？
### 22. ::bofore 和 :after 中双冒号和单冒号有什么区别？
### 23. 说下 CSS3 中一些样式的兼容，分别指兼容哪些浏览器
### 24. 有哪些手段可以优化 CSS, 提高性能
### 25. 怎么样实现边框 0.5 个像素？
### 26. 居中
### 27. transform translate transition



## 编程题

### 1. JS 字符串使用堆栈处理 "(a,b,(c,d),f,g)"

### 2. 二维数组操作

### 3. 用最简单的方式，求一个数组中最大的元素，例如 arr=[5,7,9,42,18,29]

### 4. 正则表达式，验证手机号码，验证规则：11位数字，以1位开头

### 5. 以下代码求结果

```js
function SuperClass() {
    this.name = "women";
    this.bra = ["a", "b"];
}

SuperClass.prototype.sayWhat = function() {
    console.log("hello")
}

function SubClass() {
    this.subname = "you sister";
    SuperClass.call(this);
}

var sub = new SubClass();
console.log(sub.sayWhat());
```

### 6. 当 click 点击新闻列表 Li （DOM节点）时，收集当前新闻的索引，新闻名称，新闻链接，并使用JSONP方式向地址（http://sina.cn/）上报，住：使用原生 JavaScript 实现，兼容 IE 和标准浏览器

```js
<ul>
    <li><a href="http://weibo.cn">微博</a></li>
    <li><a href="http://sina.cn">新浪</a></li>
</ul>
```

### 7. 请给 Array 本地对象增加一个原型方法，他的用途是删除数组中重复的条目并按升序排序，最后返回新数组。

### 8. 为字符串扩展一个 rewrite 函数，接收一个正则 pattern 和一个字符串 result,如果该字符串符合pattern， 则以 result 对结果进行转义输出。 如

```js
'/foo'.rewrite(/^\/foo/, '/bar')
'u1234'.rewrite(/^\/u(\d+)/, '/user/$1')
'/i'.rewrite(/^\o/, '/ooo')
```

### 9. 实现一个 js 对象序列化函数，将 js 对象序列化为可反序列化的代码，要求1.尽量和json兼容，2.支持不可序列化的值，如undefined/NaN/Infinify-Infinity，3. 支持特殊对象，如正则、Date等
```js
serialize({})
serialize({ a: 'b' })
serialize({ a: 0/0 })
serialize({ a: /foo/ })
```

### 10. 设计一道 JavaScript 的 range 算法如下：

``` js
range(1, 10, 3) 返回 [1, 4, 7, 10];
range('A', 'F', 2) 返回 ['A', 'C', 'E']
// 请使用 JavaScript 语言实现该功能（可以使用 ES6）
```

### 11. 头条的视频网站上支持了弹幕，假设一个视频有很多弹幕，弹幕的数据是一个数组，格式定义如下：
```js
[
    {
        time: Number,
        content: String
    },
    {
        time: Number,
        content: String
    }...
]
(其中 time 表示时间，content表示弹幕内容)，那么如何快速定位到某个时间点的弹幕，请编码实现（不使用数组的 sort 方法）
```

### 12. 请写出以下代码的执行结果

```js
(function() {
    fn();
    var fn = function() {
        alert(1);
    }
    fn();
    function fn() {
        alert(2)
    }
})()
```

### 13. 请说明以下各种情况的执行结果，并注明产生对应结果的理由

```js
function doSomething() {
    alert(this);
}

a) element.onclick = doSomething, 点击 element 元素后
b) element.onclick = function() doSomething(){}, 点击 element 元素后
c) 直接执行 doSomething()
```

### 14. 请写出以下代码的执行结果

```js
var obj = {};
var events = { m1: "clicked", m2: "changed"};
for(e in events) {
    obj[e] = function() {
        alert(events[e])
    }
}

alert(obj.m1 == obj.m2);
obj.m1();
obj.m2();
```


### 15. 请写出类 Son 继承类 Father

```js
function Father() {}
function Son() {}
```

### 16. 请用 JS 写出一个遍历 DOM 节点树的方法


### 17. 尝试实现注释部分的 JavaScript 代码， 可在其他任何地方添加更多代码。

```js
var Obj = function(msg) {
    this.msg = msg;
    this.shout = function () {
        alert(this.msg)
    }
    this.waitAndShout = function() {
        // 隔五秒钟后执行上面的 shout 方法
    }
}
```

### 18. 请编写一个 JavaScript 函数 parseQuerySting, 它的用途是把 URL 参数解析为一个对象，如

```js
var url = "http://www.58.com/index.aspx?key0=0&key1=1&key2=2..."
var obj = parseQuerySting(url);
alert(obj.key0) // 输出 0
```

### 19. 请给 Array 本地对象添加一个原型方法，它用于删除数组条目中重复的条目（可能有多个重复），返回值是一个包含被删除的重复条目的新数组


### 20. 我们把一个数字倒着读和原数字相同的数字称之为对称数，例如（1, 121, 88, 8998）,不考虑性能，请找出 1 - 10000 之间的对称数，要求用 JS 实现

### 21. 以下代码输出多少

```js
var name = "world";
(function () {
    if (typeof name === "undefined") {
        var name = "jack";
        console.log("Hi!" + name);
    } else {
        console.log("Hello," + name)
    }
})()
```

### 22. 数组拍平

## 框架/工程/项目
 
### 1. webpack用法
### 2. 最具有挑战性的项目
### 3. Vue的实例生命周期
### 4. webpack plugin/loader 的区别
### 5. React 之所以速度快是因为帮组 webkit 做了虚拟 diff
### 6. React 为什么要设置 key 值
### 7. React 优势
### 8. React 很多个 setState 为什么是执行完再 render
### 9. 熟悉哪些前端框架并应用于实际项目？ 阅读过哪些前端框架源码并学到哪些？
### 10. 写过哪些前端组件
### 11. 前端组件化的理解
### 12. Vue的双向数据绑定的原理
### 13. Vue 生命周期
### 14. 有没有写过框架
### 15. 性能优化
### 16. 怎么提高首屏加载速度
### 17. Node Proxy代理服务,如何把请求指向本地
### 18. Webpack 的代码分割，异步加载资源文件
### 19. [ES6 的动态加载，如何动态import](https://github.com/ravencrown/web-interview/issues/41)
### 20. 如何启动浏览器硬件加速，小Hack
### 21. React/Vue/小程序 的语法的这些好处，坏处

























