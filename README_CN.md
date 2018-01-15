# CacheEasy

redis私有云平台

# 快速开始

## 1. 安装
直接解压获取到的压缩包即可.

    tar jxvf cacheeasy-x.x.x.tar.bz2
    
## 2. 配置
解压后进入cacheeasy目录，修改conf/cacheeasy.conf文件，提供**server_name**值, 一般直接填入当前运行CacheEasy服务的机器IP即可.

例如：

    server_name = 10.3.4.5

## 3. 启动

    ./control.sh start
    
## 4. 访问站点
打开浏览器访问以下地址进入平台

    http://server_name:7800

## 5. 登录并且修改密码
用**admin**用户登录CacheEasy, 初始密码在conf/cacheeasy.conf中指定,没有修改的话默认密码是**admin**.启动服务后应尽快登录以修改默认密码。

## 6. 添加机器

## 7. 创建集群

