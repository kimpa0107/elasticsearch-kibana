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

#### 3. config

Elasticsearch config目录下有以下配置文件

```bash
role_mapping.yml
roles.yml
users
users_roles
```
后4个配置文件默认都为空，按需配置
