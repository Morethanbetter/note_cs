# 安装和卸载yum

```shell
# 安装
$ rpm -i yum-version.rpm
# 卸载
$ rpm -e yum
```

# yum的配置文件

## 公共配置

/etc/yum.conf

```shell
# 主名称，固定名称
[main]
# 缓存目录
cachedir=/var/cache/yum/$basearch/$releasever
# 要不要保存缓存
keepcache=0
debuglevel=2
logfile=/var/log/yum.log
# 要不要做精确严格的平台匹配
exactarch=1
obsoletes=1
# 检查来源法性和完整性
gpgcheck=1
# 要不要支持插件
plugins=1
# 同时安装几个
installonly_limit=5
bugtracker_url=http://bugs.centos.org/set_project.php?project_id=23&ref=http://bugs.centos.org/bug_report_page.php?category=yum
distroverpkg=centos-release
```

## 仓库配置

/etc/yum.repos.d/*.repo

```shell
# TODO
```

# yum命令

