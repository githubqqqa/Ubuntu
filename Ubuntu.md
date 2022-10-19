## 查询linux外部端口命令：

https://blog.csdn.net/liangkaiping0525/article/details/89710710

##### 

向日葵linux Ubuntu图形界面卸载指令
```
sudo apt-get --purge remove sunloginclient
```

向日葵linux Ubuntu图形界面安装指令
```
sudo dpkg -i 文件名.deb
```

甲骨文Ubuntu开启端口防火墙
```
iptables -I INPUT -p tcp --dport 填入你需要的端口 -j ACCEPT
```

开启bbr加速和开启ROOT登录
```
wget --no-check-certificate https://raw.githubusercontent.com/jinwyp/one_click_script/master/trojan_v2ray_install.sh && chmod +x ./trojan_v2ray_install.sh && ./trojan_v2ray_install.sh
```
