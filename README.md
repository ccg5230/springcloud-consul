# springcloud-consul 项目
===

## 模块

consul-config
----------------------------
consul-config：读取远端配置

consul-consumer-discoveryclient
----------------------------
ConsulDiscoveryclient不支持服务名称自定义tag解决

consul-consumer-ribbon
----------------------------
feign客户端，调用consul-provider 服务时, 使用 tag1 对应的实例

consul-provider
----------------------------
consul服务提供方

consul-provider-tag-1
----------------------------
服务提供方自定义tag1

consul-provider-tag-2
----------------------------
服务提供方自定义tag1

core-service
----------------------------
核心公共模块，提供微服务之间调用时鉴权

springcloud-gateway
----------------------------
网关


## 题外话

### 1）鉴于 Eureka 已经闭源，Hystrix已经停止维护（官方推荐替代产品是Resilicence4J），Zuul同属Netflix公司，新项目使用springcloud最好不要使用Eureka,毕竟已经闭源使用起来总有后顾之忧。


### 2）鉴于Consul的优势，采用 Consul +Spring Cloud Gateway是更好的选择


    Spring Cloud生态正经历着一些变化，前有Eureka闭源，后有Hystrix停止开发新功能。

    同时，Spring Cloud也从依赖生态伙伴提供关键组件，演变到自己开发适配关键组件，例如提供了：

    Spring Cloud Zuul；

    Spring Cloud Config；

    Spring Cloud Loadbalance；

    等开源产品。相信这才是Spring Cloud生态的最好姿态，逐渐的整合，才能为更多的开发者提供舒心的服务！
    学无止境，继续关注Spring Cloud技术发展，当然Dubbo也是可选方案！

