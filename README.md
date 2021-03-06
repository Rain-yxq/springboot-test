# springboot-test

## springboot-01

包含springboot的hello world程序，以及对主配置类的演示。

## springboot-02

主要演示springboot的一些配置规则，如application.properties、application.yml，以及一些配置的细节。

## springboot-02-config2

演示springboot的自动加载配置文件以及加载的优先级，外部加载等。

## springboot-02-config3

讲解springboot自动配置的原理。

## springboot-03-logging
1. 讲解了日志框架的体系--日志门面抽象驱动框架、日志的具体实现框架。
2. 讲解了项目中集成了多个框架，而每个框架都有自己的日志框架，对于这种情况应该怎么统一日志框架的问题。
3. 讲解了spring boot中日志框架（slf4j+logback）的使用。
4. 讲解了如何在spring boot中使用自定义的日志配置文件以及日志profile高级功能。
5. 讲解了spring boot中如何由默认logback实现切换成其他的日志框架实现。

## springboot-04-web01
spring boot的web开发
1. 静态资源映射
2. Thymeleaf模板引擎的介绍与使用
3. SpringMVC自动配置原理
4. 登录国家化
5. 拦截器进行登录检查
6. Restful风格的CRUD开发试验
7. 错误处理机制
8. 嵌入式Servlet容器

## springboot-04-web02
主要演示使用外置的Servlet容器及其启动原理

## springboot-06-data01-jdbc
由于第五章是docker的内容，没有代码，因此没有springboot-05
1. 演示spring boot的数据访问--jdbc。
2. 将数据源替换为Druid。

## springboot-06-data02-mybatis
演示spring boot整合mybatis

## springboot-07
spring boot的启动配置原理

## wrain-spring-boot-starter
自定义的starter，依赖wrain-spring-boot-starter-autoconfigurer自动配置模块

## wrain-spring-boot-starter-autoconfigurer
自定义starter的自动配置模块

## springboot-08-starter-test
测试自定义的starter