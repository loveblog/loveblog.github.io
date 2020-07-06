# Install Guide

## Rely 依赖检查

Love Blog is rely on `bash`, `gcc` and `git`, install rely on `wget`, so please install them first.

Love Blog 依赖于`Bash` `gcc` `git` `wget` ，所以请确保已经安装上述软件。

### Linux

- Arch/Manjaro `sudo pacman -S bash git wget gcc`
- Ubuntu/Debian `sudo apt-get install bash git wget gcc`
- CentOS `sudo yum install bash git wget gcc`

### MacOS

- HomeBrew `brew install bash git wget gcc`
- Apt `sudo apt-get install bash git wget gcc`

You can also install without package-mamager
你也可以不使用文件管理器安装软件

## Install 安装

### Install with CDN 使用CDN进行安装

```bash
wget https://cdn.jsdelivr.net/gh/loveblog/love-blog/install.sh -O install-lb.sh
bash install-lb.sh
```

### Install with GitHub tag 使用GitHub源码进行安装

[Get install file](https://github.com/loveblog/love-blog/blob/master/install.sh)

1. Downloads `install.sh` 下载安装文件
2. Put file into HOME-dir, (Like USER:TEST, HOME-dir:/home/TEST (/USERS/TEST in MacOS)) 放到家目录
3. `bash install.sh`

- Some questions 存在问题?

Creat a Issue on loveblog/love-blog 在loveblog/love-blog仓库中提交issue!

