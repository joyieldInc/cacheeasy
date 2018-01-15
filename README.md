# CacheEasy

A redis private cloud platform

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

## 5. Login and change password
Login CacheEasy with username **admin**, the admin password can get in conf/cacheeasy.conf, default is **admin** too. You must login admin with default password and change it ASAP.

## 6. Add Machine

## 7. Create Cluster

