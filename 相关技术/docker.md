# docker

## docker文件挂载与端口映射
-p {容器外端口}：{容器内端口}
-v {容器外路径}:{容器内路径}

## dockers常用命令
### 容器操作
docker run {镜像名} 创建容器
docker ps 查看启动中的容器
docker ps -a 查看所有容器
docker start {容器名} 启动容器
docker stop {容器名} 关闭容器
docker rm {容器名} 删除容器
docker exec -it {容器名} {待执行命令} 