SpringBoot通过导入nacos-discovery-spring-boot-starter依赖进行整合nacos时,nacos注册中心只提供服务注册和服务发现和动态配置,不提供服务可用性监测机制.

nacos的每个服务(临时服务或持久化服务)只能包含一种服务实例(临时实例或持久化实例).临时实例主动向NacosServer发送请求确保服务健康(客户端主动上报:心跳监测机制),持久化实例需要NacosServer反向确保实例健康(服务端主动下探检测:TCP,HTTP,MySQL)