# ssh
利用ssh进行远程控制同时还可以建立一个安全隧道 。如果用iodine+ssh  还可以强力穿透。
# ssh
利用ssh进行远程控制同时还可以建立一个安全隧道 。如果用iodine+ssh  还可以强力穿透。
ssh端口 22
登陆方式:使用账号和密码

iodine
注意:默认这款软件可以监听和使用所有的子域连接。

domain 
主域 @及* ( 这里的星代表 主域下所有的子域)

BangtanBoys.eu.org
worldbomb.eu.org
BigHit.eu.org
Bangtan.eu.org

BangtanBoys.top(国内) 
worldbomb.top(国内)
BigHit.top(国内)
Bangtan.top(国内)

BangtanBoys.info(国外)
worldbomb.info(国外)
BigHit.info(国外)
Bangtan.info(国外)


子域及* ( 这里的星代表 子域下所有的多级子域)

tun.BangtanBoys.eu.org
tun.worldbomb.eu.org
tun.BigHit.eu.org
tun.Bangtan.eu.org

tun.BangtanBoys.top(国内) 
tun.worldbomb.top(国内)
tun.BigHit.top(国内)
tun.Bangtan.top(国内)

tun.BangtanBoys.info(国外)
tun.worldbomb.info(国外)
tun.BigHit.info(国外)
tun.Bangtan.info(国外)


tunnel.BangtanBoys.eu.org
tunnel.worldbomb.eu.org
tunnel.BigHit.eu.org
tunnel.Bangtan.eu.org

tunnel.BangtanBoys.top(国内) 
tunnel.worldbomb.top(国内)
tunnel.BigHit.top(国内)
tunnel.Bangtan.top(国内)

tunnel.BangtanBoys.info(国外)
tunnel.worldbomb.info(国外)
tunnel.BigHit.info(国外)
tunnel.Bangtan.info(国外)


dnstunnel.BangtanBoys.eu.org
dnstunnel.worldbomb.eu.org
dnstunnel.BigHit.eu.org
dnstunnel.Bangtan.eu.org

dnstunnel.BangtanBoys.top(国内) 
dnstunnel.worldbomb.top(国内)
dnstunnel.BigHit.top(国内)
dnstunnel.Bangtan.top(国内)

dnstunnel.BangtanBoys.info(国外)
dnstunnel.worldbomb.info(国外)
dnstunnel.BigHit.info(国外)
dnstunnel.Bangtan.info(国外)


服务器
使用动态域名
ddns 


ddns.BangtanBoys.eu.org
ddns.worldbomb.eu.org
ddns.BigHit.eu.org
ddns.Bangtan.eu.org

ddns.BangtanBoys.top(国内) 
ddns.worldbomb.top(国内)
ddns.BigHit.top(国内)
ddns.Bangtan.top(国内)

ddns.BangtanBoys.info(国外)
ddns.worldbomb.info(国外)
ddns.BigHit.info(国外)
ddns.Bangtan.info(国外)指向服务器
iodine


iodine.BangtanBoys.eu.org
iodine.worldbomb.eu.org
iodine.BigHit.eu.org
iodine.Bangtan.eu.org

iodine.BangtanBoys.top(国内) 
iodine.worldbomb.top(国内)
iodine.BigHit.top(国内)
iodine.Bangtan.top(国内)

iodine.BangtanBoys.info(国外)
iodine.worldbomb.info(国外)
iodine.BigHit.info(国外)
iodine.Bangtan.info(国外)通过反向代理连接 隐藏IP并且加速。 同时还可以防止真实服务器被墙。
cache dnscache

cache.BangtanBoys.eu.org
cache.worldbomb.eu.org
cache.BigHit.eu.org
cache.Bangtan.eu.org

cache.BangtanBoys.top(国内) 
cache.worldbomb.top(国内)
cache.BigHit.top(国内)
cache.Bangtan.top(国内)

cache.BangtanBoys.info(国外)
cache.worldbomb.info(国外)
cache.BigHit.info(国外)
cache.Bangtan.info(国外)


dnscache.BangtanBoys.eu.org
dnscache.worldbomb.eu.org
dnscache.BigHit.eu.org
dnscache.Bangtan.eu.org

dnscache.BangtanBoys.top(国内) 
dnscache.worldbomb.top(国内)
dnscache.BigHit.top(国内)
dnscache.Bangtan.top(国内)

dnscache.BangtanBoys.info(国外)
dnscache.worldbomb.info(国外)
dnscache.BigHit.info(国外)
dnscache.Bangtan.info(国外)
IP地址
内网IP:192.168.0.1（老系统) 192.168.137.1（新系统）

密码:Hdy673@418



iodined.exe -f -c -DDDD -d iodine -P Hdy673@418 192.168.0/137.1 *(所使用的域名)




新的系统把提醒的服务关闭之后 通过添加服务的方式 用system权限 实现开机自启动。


sc Create 自动启动 binPath= "cmd /K start  iodined.exe -f -c -DDDD -d iodine -P Hdy673@418 192.168.0/137.1 *(所使用的域名)" type= own type= interact start= AUTO  

sc start 自动启动

