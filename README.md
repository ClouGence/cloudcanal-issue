- [Official site](https://www.clougence.com)

- [Official communitiy](https://www.askcug.com/)
                        
- [中文教程](https://www.askcug.com/topic/88/cloudcanal-docker-hub%E9%95%9C%E5%83%8F%E5%AE%89%E8%A3%85)


# What is CloudCanal
CloudCanal is a data integration platform released by ClouGence. 


- Schema Migration

 CloudCanal can help user do schema migration betweeen different data source type.


- Full Migration

CloudCanal can help user do full data transmission betweeen different data source type.

- Change Data Capture

CloudCanal can help user to sync the realtime data

- Data Compare

Compare your source and target data and know the missing data or in-consistent data.
         
- Data Revise

Revise your missing data and in-consistent data.
         
- Data Process

Filter column by condition and do some data process is also supported


- Monitor&Alert

CloudCanal is a data integration platform and you can config monitor and alert if task is in exception or task is delayed.

# Quick start
## Download the manager scripts
You can download manager shell scripts for cloudcanal docker images from here:

```
curl -O https://cloudcanal-community.oss-cn-hangzhou.aliyuncs.com/docker/1.0.0/cloudcanal_scripts_1_0_0.zip
unzip cloudcanal_scripts_1_0_0.zip
```



## Pull all the related CloudCanal images
Pay attention that the tags need to be consistent.
```java
docker pull clougence/cloudcanal-console:1.0.0
docker pull clougence/cloudcanal-sidecar:1.0.0
docker pull clougence/cloudcanal-mysql:1.0.0
docker pull clougence/cloudcanal-prometheus:1.0.0
```
## Use the manager scripts to start CloudCanal


Unzip the manager scripts and execute 
```java
sh startup.sh
```


When you see the following info, you can access the CloudCanal console from browser.
```java
cloudcanal start!!!
```
Visit localhost address https://127.0.0.1:8111 and then you can see the control.


We have created account for you.
```java
UserName: test@clougence.com
Password:  clougence2021
```

# How to submit issue ?
You can submit your issue to our [github repository](https://github.com/ClouGence/cloudcanal-issue)

# How to contact us and get support
You can access [this web page ](https://www.askcug.com/topic/75/cloudcanal%E7%A4%BE%E5%8C%BA%E7%89%88docker%E7%89%88%E5%AE%89%E8%A3%85-linux-macos/2)and find the wechat QR code at the end of the content. You also can replay in this page if you have any questions.
