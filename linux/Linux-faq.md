# 无法连接网络
```shell
# 1. 查看网关
route -n

# 设置默认网关
route add default gw 10.8.30.1

# 2. 以上不行执行下面命令
dhclient eno1
```