# 阿里的RPC

提供对Dubbo和HSF两个RPC框架的支持。

- 第一代：``Dubbo``

阿里巴巴第一代RPC框架Dubbo是国内第一款成熟的商用级RPC框架，已于2011年正式对外开源，目前已发展成为国内开源价值最高、用户使用规模最大的开源软件之一。

- 第二代：``HSF``

最新一代RPC框架HSF，全称``High Speed Framework``，也叫"好舒服"，"很舒服"框架，是阿里内部对这一款高性能服务框架的昵称，是一款面向企业级互联网架构量身定制的分布式服务框架。HSF以高性能网络通信框架为基础，提供了诸如服务发布与注册，服务调用，服务路由，服务鉴权，服务限流，服务降级和服务调用链路跟踪等一系列久经考验的功能特性。

注意功能：``API Gateway``的功能
- 服务发布与注册
- 服务调用
- 服务路由
- 服务鉴权
- **服务限流**
- 服务降级
- **服务调用链路跟踪**


为什么``HSF``性能高呢？因为 **异步** 模型。