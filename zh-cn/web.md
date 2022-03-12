## 网站
网站(Website)是指在因特网上根据一定的规则，使用HTML（超文本标记语言）等工具制作的用于展示特定内容相关网页的集合。简单地说，网站是一种沟通工具，人们可以通过网站来发布自己想要公开的资讯，或者利用网站来提供相关的网络服务。人们可以通过网页浏览器来访问网站，获取自己需要的资讯或者享受网络服务。  

> 引自：[百度百科](https://baike.baidu.com/item/%E7%BD%91%E7%AB%99/155722)  
## 准备
非常感谢这些教程的编写者，正是有了你们的乐于分享，编程才变得易懂。  

- 集成开发环境[IntelliJ IDEA介绍](https://cdk8s.gitbook.io/github/)
此教程介绍IntelliJ IDEA非常详细，我再补充一下：
1. 关于IntelliJ IDEA有旗舰版和社区版之分，旗舰版首次有30天免费试用，社区版永久免费，功能较旗舰版少了很多，如果想让开发环境更加顺畅建议还是购买旗舰版（特别是初学者），如果你是学生、老师、辅助教学、非商业开源项目都可以免费使用旗舰版，具体点击[链接](https://www.jetbrains.com/zh-cn/idea/buy/#discounts?billing=yearly) | [免费教育许可证](https://www.jetbrains.com/zh-cn/community/education/#students)
- JavaWeb学习，推荐书籍`《Java Web程序设计任务教程》/黑马程序员编著，--2版,--北京：人民邮电出版社，2021.9`
- [前端学习路线](https://objtube.github.io/front-end-roadmap/#/)
- [尚硅谷Java学习路线](https://www.bilibili.com/read/cv5216534?spm_id_from=333.788.b_636f6d6d656e74.8)
- [Spring]()

## 开发框架
web项目使用的框架：
~~VUE + Spring + python~~

## Servlet
Servlet技术，Servlet运行在web服务器上的应用程序，它是使用Java语言编写的  

Servlet体系结构：
图片  
Servlet的请求首先会被HTTP服务器（列如apache）接收，HTTP服务器只负责静态HTML页面的解析，而Servlet的请求则转交给Servlet容器，Servlet容器会根据请求路径以及Servlet之间的映射关系，调用相应的Servlet，Servlet将处理结果返回给Servlet容器，并通过HTTP服务器将响应传输给客户端。
