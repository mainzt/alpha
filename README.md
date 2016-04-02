## SpringMVC-Spring-MyBatis 集成开发平台

### 1. 基本概念
#### 1.1 `Spring`
`Spring` 是一个轻量级的控制反转（ IoC ）和面向切面（ AOP ）的容器框架。

#### 1.2 `SpringMVC`
`Spring MVC`分离了控制器、模型对象、分派器以及处理程序对象的角色，这种分离让它们更容易进行定制。

#### 1.4 `MyBatis`
`MyBatis`是一个基于`Java`的持久层框架。用简单的`XML`或注解(`annotation`)用于配置接口与sql的映射，以及Java对象与数据库记录之间的映射。

###　2. 开发环境搭建
####　2.1 `Java`环境及`Tomcat`环境
oracle官网下载JDK，apache tomcat官网下载tomcat解压版。直接安装JDK，解压tomcat后，统一配置path。假设jdk和tomcat安装在`D:\ProgramFiles`目录下，那么配置方法如下：
打开`系统属性 -> 环境变量 -> 系统变量`，新建一下几变量并赋值：
```
JAVA_HOME:D:\ProgramFiles\Java\jdk1.8.0_60
CLASSPATH:.;%JAVA_HOME%\lib;
CATALINA_BASE:D:\ProgramFiles\apache-tomcat-7.0.57
CATALINA_HOME:D:\ProgramFiles\apache-tomcat-7.0.57
```

编辑`path`，在后面添加 `;%JAVA_HOME%\bin;%CATALINA_HOME%\bin;` 

开发所用IDE为eclipse Java EE Mars
