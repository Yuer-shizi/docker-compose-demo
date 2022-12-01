## 参考文档
[nacos-docker 项目](https://github.com/nacos-group/nacos-docker/blob/v2.1.2/README_ZH.md)

## 使用教程
### 初始化数据库
1。创建数据库
nacos_conf

2。初始化表
mysql-schema.sql

3。修改 compose.yml 数据库信息

4。启动
```shell
docker-compose up -d
```
或
```shell
docker compose up -d
```
