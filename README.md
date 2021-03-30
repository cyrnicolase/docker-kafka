# docker 管理kafka与zookeeper集群

使用docker-compose 启动服务

## 配置
- 3 台 kafka节点
- 2 台 zookeeper节点
- 使用自定义桥接网络进行网络串联通信

## 注意
1. kafka的advertised.listeners 配置，需要配置成宿主机的IP和映射端口，这样才能被宿主机访问到。