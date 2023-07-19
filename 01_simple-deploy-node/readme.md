# 基于 node、docker 的简单部署

## 使用 dockerfile

```bash

# 构建镜像
docker build -t simple-deploy-node .

#启动容器
docker run --rm -p 3000:3000 simple-deploy-node

```

## 使用 docker-compose

```bash

#构建镜像->启动容器
docker-compose up --build

```
