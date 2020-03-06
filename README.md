# xss-target
代码出处未知，当时看到网上有很多它的wp，无奈的是提供的在线靶场链接都失效了，现在找到了就分享给大家。
###### linux 虚拟机内部署：
安装php:
```bash
sudo apt-get update
sudo apt-get install php
```
部署项目：
```bash
cd /项目文件夹
php -S <ip>:<port> 
```
想只让虚拟机本地访问,ip请设成localhost或127.0.0.1  想让宿主机访问请将ip设成虚拟机的ip:192.168.xxx.xxx

附:[前18关writeup.](https://www.cnblogs.com/xiaomeng2333/p/11595786.html)