## 查询linux外部端口命令：

https://blog.csdn.net/liangkaiping0525/article/details/89710710

##### 

```shell
向日葵linux Ubuntu图形界面卸载指令
sudo apt-get --purge remove sunloginclient
向日葵linux Ubuntu图形界面安装指令
sudo dpkg -i 文件名.deb
甲骨文Ubuntu开启端口防火墙
iptables -I INPUT -p tcp --dport 7880 -j ACCEPT
