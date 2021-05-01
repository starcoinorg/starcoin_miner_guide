# CentOS 安装 Docker

## 一、系统环境要求

Docker 官方建议：CentOS 7 或 8；



如果安装过 Docker ，不想用了，或者需要卸载老版本（没卸载老版本的必要）：

```shell
$ sudo yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine
```

## 二、Docker 安装

### 2.1 设置 Repo

```shell
$ sudo yum install -y yum-utils
$ sudo yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo
```

### 2.2 安装 Docker 引擎

安装最新版本的 docker 和 containerd：

```shell
$  sudo yum install -y docker-ce docker-ce-cli containerd.io
```

运行 docker：

```shell
$ sudo systemctl start docker
```

设置 docker 自启动：

```shell
$ sudo systemctl enable docker
```