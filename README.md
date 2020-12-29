# springboot-study

## springboot-11-actuator
该项目是springboot的监控项目，通过http://localhost:8080/actuator进行访问

/health的endpoint，提供了关于应用健康的基础信息
/metrics endpoints展示了几个有用的度量信息，比如JVM内存使用情况、系统CPU使用情况、打开的文件等
如果获得systems.cpu.usage的详细信息，使用http://localhost:8080/actuator/metrics/system.cpu.usage
/loggers endpoint展示了应用的日志和可以让你在运行时改变日志等级
/info endpoint展示了关于应用的一般信息

## springboot-14-springwebflux
该项目是Spring2.x基于Spring5的新特性，其基于Spring官方的Reactor实现，是一种响应式的编程

## springboot-15-annotation
该demo是自定义注解