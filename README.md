~~~
此项目是基于Spring Boot的Spring Cloud项目。

------------
项目是由一个叫base的Maven项目为基础，eureka、config、zuul为子Module。
base中pom文件存放子Module的公共依赖jar；子Module中引入base。
eureka负责服务发现、注册。
config高可用的配置中心，负责从git获取配置文件。
zuul路由网关，也可做服务过滤。