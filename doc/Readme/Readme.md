---
title: nginx
date: 2018-11-18 21:27:34
updated: 2018-11-18 21:27:34
mathjax: true
categories: 
tags:
typora-root-url: nginx
typora-copy-images-to: nginx
---



# Nginx

## 基本信息

**WebSite :**    [nginx](http://nginx.org/)   [doc](http://nginx.org/en/docs/)  [doc-cn](http://tengine.taobao.org/nginx_docs/cn/docs/)

**维基百科：**   [nginx](https://en.wikipedia.org/wiki/Nginx)

**Code：**    [trac.nginx.org](http://trac.nginx.org/nginx/browser?_ga=2.189855981.711229329.1542545969-155860260.1542545969)   [GitHub](https://github.com/nginx/nginx)



 *Nginx* (engine x) 是一个高性能的HTTP和反向代理服务，也是一个IMAP/POP3/SMTP服务 

Nginx是免费的开源软件，根据类似BSD的许可条款发布。很大一部分Web服务器使用NGINX，通常作为负载均衡器。





> # 国内版本
>
> **介绍两个国内基于Nginx做了二次开发的版本：**
>
> 1. **tengine**：这个是淘宝基于Nginx做了二次开发，运用到双11 、天猫商城上面进行了检验，产品是非常的优秀。并且在上面增量很多的功能模块，提供了DSO特性。
>
>    http://tengine.taobao.org/
>
> 2. **openresty**：这个产品是之前淘宝里面的一个叫做章宜春的大牛基于Nginx做了二次开发，设计出来。在Nginx的基础上面引入 lua 解释器，可以让Nginx在不使用第三方的脚本解释器的情况下，自己就可以完成动态请求。（openresty = nginx + lua）
>
>    1. lua是由一个巴西人开发出来了一门脚本语言，专注于游戏领域的开发。lua是后端语言。
>    2. cocos2d-lua 专门做游戏开发的，还有其它，如，cocos2d-js\C++
>    3. lua火起来的原因是国内一款《大话2》，其背后的推动着是前网易的 云风（吴云洋）。（国内游戏基本上都认识这个人，天才）
>
>    http://openresty.org/cn/
>
> 总结：上面的这两个产品在国内使用的更多。成熟的解决方案就更多，文档更加符合国内情况。



## 参考阅读

> [njs ](http://nginx.org/en/docs/njs/)是JavaScript语言的一个子集，允许扩展nginx功能。
>
> * 在请求到达上游服务器之前，njs中的复杂访问控制和安全性检查
> * 操纵响应标头
> * 编写灵活的异步内容处理程序和过滤器



[Nginx中文](http://www.nginx.cn/)

[Nginx中文文档](http://www.nginx.cn/doc/)

[Nginx开发从入门到精通 - tengine](http://tengine.taobao.org/book/)





