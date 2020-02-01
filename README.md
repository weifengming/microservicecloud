# microservicecloud
微服务框架集成

服务提供者：microservicecloud-provider-dept-8001端口：8001

测试Ribbon负载均衡：microservicecloud-provider-dept-8002端口：8002，microservicecloud-provider-dept-8003端口：8003

服务消费者：microservicecloud-consumer-dept-80端口：80

Eureka注册中心：microservicecloud-eureka-7001端口：7001

Eureka集群：microservicecloud-eureka-7002端口：7002，microservicecloud-eureka-7003端口：7003

microservicecloud-consumer-dept-80中新增ribbon自定义，主启动类中注释了负载规则
