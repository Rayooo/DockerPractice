拉取ZK的镜像 && 运行

```shell
$ docker pull zookeeper 
$ docker run --name zk -d -p 2181:2181 -p 2888:2888 -p 3888:3888  zookeeper
```