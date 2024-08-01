# Centos修改yum源为阿里源

## 备份系统自带yum源配置文件

```shell
mv /etc/yum.repos.d/CentOS-Base.repo /etc/yum.repos.d/CentOS-Base.repo.backup
```

## 下载ailiyun的yum源配置文件

### CentOS7

```shell
wget -O /etc/yum.repos.d/CentOS-Base.repo http://mirrors.aliyun.com/repo/Centos-7.repo
```

### CentOS6

```shell
wget -O /etc/yum.repos.d/CentOS-Base.repo http://mirrors.aliyun.com/repo/Centos-6.repo
```

## 重新生成缓存

```shell
yum makecache
```
