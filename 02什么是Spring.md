# 什么是Spring

Spring是一个开源框架，2003年兴起的轻量级java开发框架，RodJohnson



**Spring是为了解决企业级应用开发的复杂性而创建的，简化开发**

# Spring是如何简化Java开发的

1、基于POJO的轻量级和最小侵入性编程（bean）

2、通过IOC，依赖注入（DI）和面向接口实现松耦合

3、基于AOP和惯例进行声明式编程

4、通过切面和模板（template）减少样式代码

# 什么是SpringBoot

一个javaweb开发框架，和SpringMVC类似

JavaEE->Spring->SpringBoot

**SpringBoot以约定大于配置**

# 微服务：什么是微服务

微服务是一种架构风格   Resultful风格是针对接口来说的

MVC三层架构（model层、view层、controller层）、MVVM前端架构、微服务架构

微服务想成一个个的业务：service：userService===>模块！

SpringMVC，Controller==>提供接口

可以通过HTTP通信、RPC通信等

数据库访问（dao层）、web访问（controller层）

例子：用户下单 就是一个controller  1s

消息队列：

仓库冻结：资金冻结：验证：购买成功：仓库数量减少：仓库解冻：资金解冻  10s

