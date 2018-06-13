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
