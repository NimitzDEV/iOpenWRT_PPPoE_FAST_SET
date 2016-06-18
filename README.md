## 适用于 OpenWRT 的 PPPoE 快速设置接口 ##


----------

适用于使用动态密码的网络环境，要进行快速设置，请配合密码获取端使用

[OpenWRT版本](https://github.com/NimitzDEV/AutoConnectADSL/tree/openwrt)

[磊科路由器没有登录密码版本](https://github.com/NimitzDEV/AutoConnectADSL/tree/master)

本程序是一个 CGI 程序，使用 shell 编写

使用方法

 - 使用软件进入路由器的 FTP 
 - 切换到 HTTP 服务文件存放目录 (例如 /www)
 - 将 fast 文件放到 cgi-bin 中
 - 使用软件登录 SSH
 - 赋予 fast 对应的权限 (至少711)
 - 访问该文件，pppoeun 参数为 PPPOE 用户名，pppoepwd 参数为 PPPOE 密码