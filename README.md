# aria2
这里主要用于收集利用VPS搭建离线PT下载到Onedrive所需要的脚本。
##
主要的安装步骤如下：
第一步
<wget -N --no-check-certificate https://raw.githubusercontent.com/leexff/aria2/master/aria2.sh && chmod +x aria2.sh && bash aria2.sh>

1、安装aria2.sh
选择1，然后一直默认安装。

2、安装install.sh （即BT面板）
安装完毕后，会显示你的登陆页面和用户名，密码。记好了。
在浏览器里输入你的ip:8888 ，输入用户名和密码后登陆宝塔面板：
这里只需要安装Nginx和php5.6就可以了，其他FTP，Mysql不需要。
