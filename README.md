# CacheEasy [中文版](https://github.com/joyieldInc/cacheeasy/blob/master/README_CN.md)

A redis private cloud platform

# Features

+ Supports redis standalone and redis cluster
+ Uses redis sentinel for redis standalone automatic
+ With redis proxy [predixy](https://github.com/joyieldInc/predixy), the redis client don't consider redis sentinel or redis cluster
+ Create redis service quickly
+ Show service status by Grafana
+ Scale redis service easy
+ Alert monitor
+ Easy to use, don't require root

# QuickStart

## 1. Install
Just get the release package, then unpack it.

    tar jxvf cacheeasy-x.x.x.tar.bz2
    
## 2. Configuration
Enter the cacheeasy directory, modify the conf/cacheeasy.conf, provide the **server_name** value, in generally, it's the IP of the machine you running CacheEasy.

eg.

    server_name = 10.3.4.5

## 3. Start

    ./control.sh start
    
## 4. Visit
Open your browser and visit

    http://server_name:7800

