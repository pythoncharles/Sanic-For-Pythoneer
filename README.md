## Sanic-For-Pythoner

> 这是一份记录文档，是我日常对`Sanic`使用过程中一些问题的记录
>
> 虽说是大杂烩，但我也会尽量使其连贯，或许能使一些人在使用Sanic的过程中少走一些弯路
>
> 可根据需求跳跃阅读

### 1.介绍

`Sanic`是一个可以使用async/await 语法编写项目的异步非阻塞框架，我于2017年2月份就开始使用`Sanic`，使用过程中确实遇到不少问题，如缓存、模板引入、session、认证...

但不用担心，`Sanic`更新速度非常快，比如说接口`token`认证，当时的版本我是直接手写一个`decorators`进行验证，如今`request`类则直接有`token`方法进行获取，但对其他`headers`头的验证，还是写个`decorators`比较全面

总是，个人觉得`Sanic`是一个值得尝试的异步框架，不论是代码编写还是性能比较

本项目的结构如下：

- [1.初使用](./docs/1.初使用.md) - 2017-07-23
- [2.配置](./docs/2.配置.md)


### 2.更新

代码的世界变幻莫测，我能做的就是将本篇文档持续更新、持续修正、让其处于当前最新的状态