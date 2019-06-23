# UbuntuEnv


使用 Ubuntu 的 NUC 定制版本 16.04LTS

安装以后要升级，不升级应该有bug没有修复（主要是WiFi）


## 安装 openssl-server 包
* apt-get install -y openssl-server
* sudo systemctl restart ssh
* sudo systemctl enable ssh

## Wifi
通过UI，设置WiFi的IP地址，使用 menual 指定 固定IP 的方式

Login 之前连接WiFi，
psk-flags=0



## 防止休眠
sudo systemctl mask sleep.target suspend.target hibernate.target hybrid-sleep.target



## 安装远程桌面
sudo apt-get install x11vnc


