# Docker 部署AppSpace文档


## 版本列表

- 稳定版本 - app-space/latest - `ghcr.io/appspa/app-space:latest`

## 镜像仓库

- Github Container Registry: https://github.com/appspa/app-space/pkgs/container/app-space (**推荐**)

## 第一步
### 安装 Docker

按照[官方教程](https://get.docker.com/)安装

[//]: # (### 安装 Docker-Compose)

[//]: # ()
[//]: # (按照[官方教程]&#40;https://docs.docker.com/compose/install/&#41;安装)

## 第二步
### 下载App-Space-docker
```angular2html
git clone https://github.com/appspa/app-space-docker.git
```
## 第三步
### .env 配置
自定义参数 例如:域名 存储

## 第四步
### 编译
```angular2html
docker-compose up -d --build
```
## 第五步
### 访问
[http://localhost/](http://localhost/)



