# minio

## 修改服务端口号：
server /data --address ":19000" --console-address ":9001"

--address：

可选项将 minio 服务器进程绑定到特定的网络地址和端口号。将地址和端口指定为 ADDRESS:PORT，其中 ADDRESS 是 IP 地址或主机名，PORT 是主机系统上的有效和打开的端口。
若要更改在主机上配置的所有 IP 地址或主机名的端口号，请指定 :PORT，其中 PORT 是主机上的有效和打开端口。
如果省略，minio 将绑定到主机上所有配置的 IP 地址或主机名上的端口9000。

--console-address

web 端口

其他配置方式：
[environment-variables](https://min.io/docs/minio/linux/reference/minio-server/minio-server.html#environment-variables)
