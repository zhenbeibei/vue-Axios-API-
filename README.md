# vue-Axios-API-
vue中Axios的封装和API接口的管理-菜鸟学习记录
参考了 https://juejin.cn/post/6844903652881072141

面对一团糟代码，我们需要的说的axios的封装和api接口的统一管理，其实主要目的就是在帮助我们简化代码和利于后期的更新维护。

一、axios的封装
在vue项目中，和后台交互获取数据这块，我们通常使用的是axios库，它是基于promise的http库，可运行在浏览器端和node.js中。他有很多优秀的特性，例如拦截请求和响应、取消请求、转换json、客户端防御XSRF等。所以我们的尤大大也是果断放弃了对其官方库vue-resource的维护，直接推荐我们使用axios库。如果还对axios不了解的，可以移步axios文档。
