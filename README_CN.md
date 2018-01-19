# CacheEasy

**CacheEasy**是一款redis私有云平台软件，利用CacheEasy可以高效、可靠的维护大量redis服务。

# 特性

+ 支持经典的redis standalone模式和集群版的redis cluster模式
+ 自动采用redis sentinel实现redis standalone模式的高可用部署
+ 集成高性能、全特性的redis代理软件[predixy](https://github.com/joyieldInc/predixy)，客户端无需关心redis部署模式
+ 快速创建部署redis服务
+ 轻松扩容、缩容
+ 丰富的可视化数据展示，服务运行状态一目了然，追查问题得心应手
+ 内置报警监控系统，出现问题及时发出通知
+ 简单方便，解压即用，无需root权限

# 快速开始

## 1. 安装
直接解压获取到的[压缩包](https://github.com/joyieldInc/cacheeasy/releases)即可.

    tar jxvf cacheeasy-x.x.x.tar.bz2
    
## 2. 配置
解压后进入cacheeasy目录，修改conf/cacheeasy.conf文件，提供**server_name**值, 一般直接填入当前运行CacheEasy服务的机器IP即可.

例如：

    server_name = 10.3.4.5

## 3. 启动

    ./control.sh start
    
## 4. 访问服务
打开浏览器访问以下地址进入平台

    http://server_name:7800

# 详细使用说明

[使用说明](https://github.com/joyieldInc/cacheeasy/wiki/CacheEasy%E4%B8%AD%E6%96%87%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E)
