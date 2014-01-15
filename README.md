qbh
===

Qingtian Browser Helper(qbh), a browser helper that used to visually impaired persons.

qbh是一个浏览器助手，他的主要用途是为视障人使用浏览器提供帮助。


主要功能
===

* 改变网页的显示布局
* 隐藏页面中的某些元素
* 给页面增加某些元素或元素属性
* 其他dom操作
* 扩展浏览器window对象的功能
 为其他辅助工具提供支持（例如读屏软件）


起因
===

为什么要做这样一个浏览器助手呢？现有的读屏软件不是都支持网页浏览吗？

的确，所有的读屏软件都支持网页浏览，但是实际的情况是读屏软件的支持是一片混乱的，不同读屏软件开发者采用不同的技术实现，各自有自己的操作方法。这样对网页开发人员来说，如果要开发支持读屏软件可访问的无障碍网页，就意味着要兼容不同读屏软件，这无疑是增加了网页开发人员的开发成本。对读屏软件用户来说，不同读屏软件用户之间的交流就存在着障碍，大家无法相互交流使用经验。

基于这些因素的考虑，我想找到一种通用的解决方案，实现跨读屏软件的一种方式，或者说另开一条途径，来实现在网页浏览方面 实现统一。

chromevox是chrome浏览器的一个插件，他实现了在chrome平台下的读屏功能，采用了js作为开发语言。这给了我灵感和启发，既然在chrome可以实现，那么在其他浏览器平台也应该可以尝试。js是跨浏览器的，那么就可能实现跨浏览器的统一解决方案。

qbh要做的事情有两个层次：
===

第一，给浏览器的window对象增加心的功能，这主要是为了适应读屏软件的需要。

第二，通过js脚本来操作dom，为浏览器操作提供辅助支持。这一点实际上跟firefox下的greasemonkey和chrome下的adblock plus的工作非常相似或者就是一样的。

那么也可以理解成qbh是一个跨浏览器的adblock plus。


如果你对这个项目感兴趣，欢迎加入我们。
===

目前这个项目仅仅存在于我的大脑当中，急切的需要你的参与。

参与方式不限，贡献你的想法，参与编码，参与宣传等都非常的欢迎。

可以联系到我的方式有：

* QQ：115928478
* 微博： <http://weibo.com/qt06/>
* 邮箱： <qt06.com@139.com>