
在原版基础上稍加修改，改为rtorrent0.9.4+libtorrent0.13.4+各自的ipv6补丁
 
目前 宝塔安装环境后存在rss不能载入https的订阅链接的问题，暂未找到解决办法

其余功能正常，支持http订阅的站点以及手动添加http/https种子均无问题
 
注意 安好后需修改.rtorrent.rc文件添加ip = "你的ipv4地址" 以便汇报给tracker，否者只有ipv6地址
 
# rotorrent-install-for-centos7
rtorrent &amp; rutorrent install for centos7


本程序支持安转rtorrent+rutorrent在centos环境下进行一键安装，必须要有root权限，目前支持centos6/centos7


目前支持 lnmp安装完毕，vestacp安装完毕，apache+php-fpm安装完毕的环境
安装方法：

cd /root

wget --no-check-certificate https://raw.githubusercontent.com/pet185377/rotorrent-install-for-centos7/master/rt_ru_install.sh

chmod +x rt_ru_install.sh

./rt_ru_install.sh



更改记录：

version0.5  增加自动添加防火墙端口


version0.4  增加支持centos6下安装，修正支持了在centos6环境下安装ffmpeg


version0.35 修正支持了在vestacp环境下自动获取web网页地址功能


version0.3  支持不同环境不同的默认web网页地址配置，方便安装


version0.2  修正了部分程序安装问题



version0.1  支持在centos7下安装rutorrent+rtorrent
    
