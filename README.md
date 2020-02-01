#微服务框架集成(microservicecloud)

##工程说明
* microservicecloud-api：基础工程
* microservicecloud-provider-dept-8001：服务提供者
* microservicecloud-provider-dept-8002：服务提供者(Ribbon负载测试)
* microservicecloud-provider-dept-8003：服务提供者(Ribbon负载测试)
* microservicecloud-eureka-7001：Eureka注册中心
* microservicecloud-eureka-7002：Eureka注册中心(Eureka集群)
* microservicecloud-eureka-7003:Eureka注册中心(Eureka集群)
* microservicecloud-consumer-dept-80:服务消费者

##功能点说明
* microservicecloud-consumer-dept-80中新增ribbon自定义，主启动类中注释了负载规则
