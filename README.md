~~~
此项目是基于Spring Boot的Spring Cloud项目。

------------
项目是由一个叫base的Maven项目为基础，eureka、config、zuul为子项目。
eureka负责服务发现、注册。
config高可用的配置中心，负责从git获取配置文件。
zuul路由网关。