## MySQL 启动问题
### [ERROR] Could not use /var/log/mysql/slow.log for logging (error 13 - Permission denied). Turning logging off for the server process. To turn it on again: fix the cause, then either restart the query logging by using "SET GLOBAL SLOW_QUERY_LOG=ON" or restart the MySQL server.
```shell
chmod 777 ./logs
```
