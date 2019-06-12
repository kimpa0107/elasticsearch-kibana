# Elasticsearch & Kibana Docker

#### 1. 创建目录 && 目录权限

```bash
mkdir data plugins
chown -R 1000:root data plugins
```
> Elasticsearch docker中的目录权限 所有者：1000 所属组：root

#### 2. 下载镜像并启动容器

```bash
docker-compose up -d
```

