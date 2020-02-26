## 注意事项
    1、一键安装 Shadowsocks-Python， ShadowsocksR， Shadowsocks-Go， Shadowsocks-libev 版（四选一）服务端；
    2、各版本的启动脚本及配置文件名不再重合；
    3、每次运行可安装一种版本；
    4、支持以多次运行来安装多个版本，且各个版本可以共存（注意端口号需设成不同）；
    5、若已安装多个版本，则卸载时也需多次运行（每次卸载一种）；
    6、Shadowsocks-Python 和 ShadowsocksR 安装后不可同时启动（因为本质上都属 Python 版）。
    
### 安装
    wget --no-check-certificate -O ss.sh https://raw.githubusercontent.com/zia123-ai/shadowsocks_install/master/ss.sh&&bash ss.sh
#### 启动脚本后面的参数含义，从左至右依次为：启动，停止，重启，查看状态。

    Shadowsocks-Python 版：
    /etc/init.d/shadowsocks-python start | stop | restart | status
    ShadowsocksR 版：
    /etc/init.d/shadowsocks-r start | stop | restart | status
    Shadowsocks-Go 版：
    /etc/init.d/shadowsocks-go start | stop | restart | status
    Shadowsocks-libev 版：
    /etc/init.d/shadowsocks-libev start | stop | restart | status
#### 各版本默认配置文件
   
    Shadowsocks-Python 版：
    /etc/shadowsocks-python/config.json
    ShadowsocksR 版：
    /etc/shadowsocks-r/config.json
    Shadowsocks-Go 版：
    /etc/shadowsocks-go/config.json
    Shadowsocks-libev 版：
    /etc/shadowsocks-libev/config.json
###### [搬运自](https://www.gigsgigscloud.com/cn/tutorials/)

