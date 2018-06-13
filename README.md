# Ambari

## Install 

```
wget -nv http://public-repo-1.hortonworks.com/ambari/centos7/2.x/updates/2.4.2.0/ambari.repo -O /etc/yum.repos.d/ambari.repo

```


```
yum install ambari-server

```
## config

```
ambari-server setup

```


## use 

```
ambari-server start
ambari-server stop
ambari-server status

```



#  免密码登录问题
拷贝pub文件到两台机器上
cp id_rsa.pub 到本机和其他节点  为 authorized_keys 文件

#  ssl版本问题
禁止SSL校验
https://community.hortonworks.com/questions/145/openssl-error-upon-host-registration.html
