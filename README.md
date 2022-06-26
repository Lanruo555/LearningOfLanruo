   基于[Road To Coding](https://r2coding.com/#/README ) 学习的记录



## 一、编程语言

#### 1.1 Java语言

##### 1.1.1 语言基础 

- 基础语法

- 面向对象

- 接口

- 容器

- 异常

- 泛型

- 反射

- 注解

- I/O

- 图形化（Swing）



##### 1.1.2 JVM

- 类加载机制
- 字节码执行机制
- JVM内存模型
- GC垃圾回收机制
- JVM性能监控俞故障定位
- JVM调优



##### 1.1.3 并发/多线程

- 并发编程基础

- 线程池

- 锁

- 并发容器

- 原子类

- JUC并发工具类

  

#### 1.2 数据结构与算法

- 数据结构

  - 字符串
  - 数组
  - 链表
  - 二叉树
  - 堆、栈、队列
  - 哈希

- 算法

  - 查看
  - 排序
  - 贪心
  - 分治
  - 动态规划
  - 回溯

#### 1.3 计算机网络

- ARP协议
- IP/ICMP协议
- TCP/UDP协议
- DNS/HTTP/HTTPS协议
- Session/Cookie

#### 1.4 数据库/SQL

- SQL语句书写
- SQL语句优化
- 事务以及隔离级别
- 索引
- 锁

#### 1.5 操作系统

- 进程/线程
- 并发/锁
- 内存管理和调度
- I/O原理

#### 1.6 设计模式

- 单例
- 工厂
- 代理
- 策略
- 模板方法
- 观察者
- 适配器
- 责任链
- 建造者
- 

## 二、**研发工具**

#### 2.1 集成开发环境

- Eclipse

- Intellij IDEA

- VS Code

  

#### 2.2 Linux 系统

- Linux常用命令

- 基本shell脚本

  

#### 2.3 代码管理工具

- Git
- SVN



#### 2.4 项目管理/构建工具

- Maven
- Gradle



## 三、**应用框架**

### 后端

- **Spring家族**

  - Spring

    - IoC
    - AOP

  - Spring MVC
  - Spring Boot

    - 自动配置、开箱即用
    - 整合web
    - 整合数据库（事务问题）
    - 整合权限

      - Shiro
      - Spring Security

    - 整合各种中间件

      - 缓存
      - MQ
      - RPC框架
      - NIO框架

- **服务器软件**

  - web服务器

    - Nginx

  - 应用服务器

    - Tomcat
    - Jetty
    - Undertow

- **中间件**

  - 缓存

    - Redis

      - 5大数据类型
      - 事务
      - 消息通知
      - 管道
      - 持久化
      - 集群

    - memcache

  - 消息队列

    - RocketMQ
    - RabbitMQ
    - Kafka

  - RC框架

    - Dubbo
    - gRPC
    - Thrift
    - Spring Cloud
    - Netty

- **数据库**

  - ORM框架

    - MyBatis
    - Hibernate
    - JPA

  - 连接池

    - Druid
    - HikariCP
    - C3P0

  - 分库分表

    - MyCat
    - Sharding-JDBC
    - Sharding-Sphere

- **搜索引擎**

  - ElasticSearch
  - Solr

- **分布式/微服务**

  - 服务发现/注册

    - Eureka
    - Consul
    - Zookeeer
    - Nacos

  - 网关

    - Zuul
    - Gateway

  - 服务调用(负载均衡)

    - Ribbon
    - Feign

  - 熔断/降级

    - Hystrix

  - 配置中心

    - Config
    - Apollo
    - Nacos

  - 认证和鉴权

    - Shrio
    - Spring Security
    - Oauth2
    - SSO

  - 分布式事务

    - JTA接口 --- Atomikos组件
    - 2PC、3PC
    - XA模式
    - TCC模式

      - tcc-transaction
      - ByteTCC
      - EasyTransaction
      - Seata

    - SAGA模式

      - ServiceComb
      - Seata

    - LCN模式

      - tx-lcn

  - 任务调度

    - Quartz
    - Elastic-Job

  - 链路追踪与监控

    - Zipkin
    - Sleuth
    - Skywalking

  - 日志分析与监控

    - ELK

      - ElasticSearch
      - Logstash
      - Kibana

- **虚拟化/容器化**

  - 容器技术

    - Docker
    - 容器编排技术

      - Kubernetes
      - Swarm

### 前端

- 基础套餐

  - 三大件

    - HTML
    - JavaScript
    - CSS

  - 基础库

    - JQuery
    - Ajax

- 模板框架

  - JSP/JSTL
  - Thymeleaf
  - FreeMarker

- z组件化框架

  - Node
  - VUE
  - React
  - Angular

## 四、**运维知识**

#### 4.1 web服务器

- Nginx



#### 4.2 应用服务器

- Tomcat/Jetty/Undertow



#### 4.3 CDN加速



#### 4.4 持续集成/持续发布

- Jenkins



#### 4.5 代码质量检查

- sonar



#### 4.6 日志收集/分析

- ELK



## 五、**学无止境**

##### 徒手撕源码

##### 光脚造轮子

##### 闭眼睛深度调优

##### 无惧面试官

##### 调平心态、注意健康

