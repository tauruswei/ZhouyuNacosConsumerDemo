# ZhouyuNacosConsumerDemo
### 1、首先要启动 nacos docker 容器
```shell
git clone https://github.com/nacos-group/nacos-docker
cd nacos-docker/example
# 启动容器 
docker-compose -f example/standalone-derby.yaml up -d
```
### 2、启动 ZhouyuNacosDemo 
```shell
git clone https://github.com/tauruswei/ZhouyuNacosDemo
# 启动项目
nohup java -jar target/demo-0.0.1-SNAPSHOT.jar  --server.port=7070  &
```