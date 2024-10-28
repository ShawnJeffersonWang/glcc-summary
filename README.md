# GitLink编程夏令营（GLCC）- Apache dubbo-kubernetes 结项总结

### 课题连接
[https://github.com/apache/dubbo-kubernetes/pull/491](https://www.gitlink.org.cn/dubbo/dubbo/issues/7)

### 课题背景
Dubbo 正在建设一套面向云原生时代的控制台系统，基于这套系统可以管控整个微服务集群的状态，本赛题是出自该系统中的可视化监测部分，技术架构上会依赖 Prometheus、Grafana、Kubernetes 等。

### 课题详情
本赛题的目标是为 Dubbo 微服务集群提供完善的可视化监控能力，包括服务调用指标、服务依赖拓扑、实例健康状态等，具体监控指标诉求可参见交互稿中的指标：http://101.34.253.152:8080/2024-05-08/

### 交付说明
依赖 prometheus、grafana、控制面等能搭建起一套完整的微服务集群监控链路
实现后端服务开发，能完成指标查询、指标聚合等功能，满足规划的监控能力

**Dubbo-k8s Contributions**:
  - [[dubbo-k8s/admin] Implemented Metrics Detail List for dubbo instance](https://github.com/apache/dubbo-kubernetes/pull/319)
  - [[dubbo-k8s/admin] Implemented Service Metrics, Service Dependency, Service Topology, Service Healthy and optimize Instance Metrics for Instance and Service](https://github.com/apache/dubbo-kubernetes/pull/491)
