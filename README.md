# 说明
demo to learn java
存储本人学习Java的过程

## ExamSystem
> **模拟一个考试系统**，由GUI来显示
1. 对JavaSE知识点的一次综合练习
2. 初步认识MVC中的Model层
3. IOC控制权对象反转
4. 生命周期托管方式实现单例模式


## AtmSystem
> **模拟一个Atm系统**，由GUI来显示
1. MySQL
2. 用dao层实现jdbc


## ORM
> **模拟JDBC连接池+对ORM框架的封装**
1. properties配置文件的使用
2. 静态代理模式
3. 自定义注解的使用（dao层中用注解传输SQL语句以及各种信息），动态代理模式（使用jdk提供的动态代理类Proxy），最后把dao层变成接口


## RequestAndResponse
> **模拟请求与响应的过程**，学习J2EE之前的准备
1. B/S模式，socket和I/O
2. String解析
3. properties配置文件的使用
4. 线程，集合，面向对象
5. 对html标签的模拟

**思路：**[Servlet 模拟浏览器与服务器之间：请求与响应的过程](https://juejin.im/post/5d85ebd1f265da03b76b5cdf)

## AtmForServlet
> 使用idea和Tomcat：Servlet，HTML来实现以一个银行系统（B/S模式）

**结构**
- V（HTML，JSP）
- C（Servlet）
- M（service，dao，domain三个层次和jdbc）
- DB（MySql）

**思路：**[使用Tomcat9，模拟B/S模式的Atm系统（仅仅只使用了Servlet）](https://juejin.im/post/5d8718275188253f116b8ee7)
