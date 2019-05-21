# docker-lnmp
docker部署lnmp环境

# 简介

基于Docker官方镜像部署 LNMP (Nginx1.15, MySQL5.7, PHP7.2).

### 目录说明

```
docker-lnmp
│
├─mysql                 mysql 目录
│
├─nginx                 nginx 目录
|
├─nginx                 php 目录
│  |
|  |——php.ini           php.ini php配置文件
|
├─php-fpm               php-fpm 目录
│  └─Dockerfile         php-fpm dockerfile文件
│
├─docker-compose.yml    docker-compose 文件

```
##环境部署

使用 `docker-compose up -d` 构建并后台运行 
