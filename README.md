# 项目说明  
项目用于记录各服务配置信息  
## 目录配置  
### 注:  
#### 项目中使用的特殊符号与linux操作系统对应  
符号"～" 对应 用户家目录  
如:~/data/docker/ 指向 当前用户家目录下的/data/docker 目录  

## 目录结构  
### 1. docker  
   1. docker-compose配置文件版本说明
      1. version "3" 添加command 多命令行支持[refer to](https://docs.docker.com/ee/)
         ```
         command:
            - /bin/bash
            - -c
            - |
              cd ~/tomcat/bin/
              startup.sh
         ```
### 2. elk
### 3. git
### 4. gitlib
### 5. haproxy-keepalived
### 6. java
### 7. k8s
### 8. kafka
### 9. linux 
### 10. mongo
### 11. mysql
### 12. nexus
### 13. nginx
### 14. redis
### 15. rocketMq
   1. docker版本配置来源 [refer to](https://github.com/apache/rocketmq-docker)
### 16. zk
 

