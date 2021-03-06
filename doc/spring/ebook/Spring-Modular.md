# Spring 模块化设计

> 下列模块摘自 [Spring Framework](https://github.com/spring-projects/spring-framework)


# Spring 包介绍
- spring-aop
    - spring 切片
- spring-aspects
    - spring aspect 实现
- spring-beans
    - spring bean相关内容
- spring-context
    - Spring 上下文是一个配置文件，向 Spring 框架提供上下文信息。Spring 上下文包括企业服务，例如 JNDI、EJB、电子邮件、国际化、校验和调度功能。
- spring-context-support
    - spring 核心拓展
- spring-context-indexer
    - spring 核心分配器
- spring-core
    - spring 核心处理
- spring-expression
    - Spring Expression Language 简称SpEL Spring 表达式
- spring-instrument
    - spring 工具
- spring-jcl
    - JCL全称: Jakarta Commons Logging
    - spring-jcl 采用了设计模式中的“适配器模式”，它对外提供统一的接口，然后在适配类中将对日志的操作委托给具体的日志框架。
- spring-jdbc
    - jdbc 实现
- spring-jms
    - spring jms 实现
- spring-messaging
    - spring 消息
- spring-orm
    - Spring 框架插入了若干个 ORM 框架，从而提供了 ORM 的对象关系工具，其中包括 JDO、Hibernate 和 iBatis SQL Map。所有这些都遵从 Spring 的通用事务和 DAO 异常层次结构
- spring-oxm
    - spring object/xml对应相关
- spring-test
    - spring 测试相关内容
- spring-tx
    - spring 事物
- spring-web
    - Web 上下文模块建立在应用程序上下文模块之上，为基于 Web 的应用程序提供了上下文。所以，Spring 框架支持与 Jakarta Struts 的集成。Web 模块还简化了处理多部分请求以及将请求参数绑定到域对象的工作
- spring-webmvc
    - MVC 框架是一个全功能的构建 Web 应用程序的 MVC 实现。通过策略接口，MVC 框架变成为高度可配置的，MVC 容纳了大量视图技术，其中包括 JSP、Velocity、Tiles、iText 和 POI。
- spring-webflux
    - spring webflux是一个完全的reactive并且非阻塞的web框架。
- spring-websocket
    - spring 网络连接