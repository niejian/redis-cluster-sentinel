##redis两种方式的集群配置
###1.cluster模式
对应的配置文件在redis-cluster
默认的端口是7001=7006
###2.sentinel模式。
对应的文件在redis-sentinel中
sentinel有两个分别是sentinel1和sentinel2.端口模式27001，27002
被监控的节点分别是7001-7006.其中7003是主节点。sentinel中配置的主节点名称是mymaster
