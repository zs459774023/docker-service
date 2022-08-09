# docker-service

提供多种公共服务,如nginx、mysql、etcd等，PHP、golang 等个人理解为为业务服务，非公用。


##公用同一个网络
```shell
docker network create service-net
```

### 已支持列表
- etcd
- nginx
- mysql
- redis
- clickhouse