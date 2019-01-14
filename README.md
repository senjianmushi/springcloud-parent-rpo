# springcloud-parent-rpo
springcloud-parent的配置文件库
# springcloud-parent



项目工程结构

```
├─springcloud-parent----------------------------父项目，公共依赖
│  │
│  ├─Eureka-server-------------------------------统一鉴权中心
│  │
│  ├─cofig-server------------------------------微服务配置中心
│  │
│  ├─gateway-server----------------------------微服务网关中心【路由】
│  │
|  │─auth-server
│  │  │
│  │  │─auth-server-api-----------------------基于auth2的feign配置
│  │  │
│  │  └─auth-server-provider------------------基于auth2的feign配置
│  │
│  ├─paascloud-monitor-------------------------微服务监控中心【待开发】
│  │
│  ├─paascloud-zipkin--------------------------微服务日志采集中心【待开发】
│  │
│  ├─common
│  │  │
│  │  ├─paascloud-common-base------------------公共POJO基础包
│  │  │
│  │  ├─paascloud-common-config------------------公共配置包
│  │  │
│  │  ├─paascloud-common-core------------------微服务核心依赖包
│  │  │
│  │  ├─paascloud-common-util------------------公共工具包
│  │  │
│  │  ├─paascloud-common-zk------------------zookeeper配置
│  │  │
│  │  ├─paascloud-security-app------------------公共无状态安全认证
│  │  │
│  │  ├─paascloud-security-core------------------安全服务核心包
│  │  │
│  │  └─paascloud-security-feign------------------基于auth2的feign配置
│  │
│  ├─user-server
│  │  │
│  │  ├─user-server-api-------------------------用户服务消费者
│  │  │
│  │  └─user-server-provider--------------------用户服务提供者
│  │
│  ├─repair-server
│  │  │
│  │  ├─user-server-api-------------------------维修服务消费者
│  │  │
│  │  └─user-server-provider--------------------维修服务提供者
│  │
│  └─mybatis-generator---------------------------数据服务中心Mybatis Generator
```
