# 设计目标

* 相同key，不同请求，尽可能路由到相同机器（即使扩缩容），访问到相同的数据分片，如分布式缓存。

* 不同key，尽可能均匀路由到不同机器，负载均衡。