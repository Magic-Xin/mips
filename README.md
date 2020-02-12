# SSR for mips router with merlin koolshare firmware
* <b>原项目：https://github.com/harry3633/fancyss/tree/master/fancyss_mipsel</b>
* <b>此项目仅用于merlin koolshare mipsel架构改版固件</b>
* <b>Sock5的GFWlist.acl源自ACL4SSR：https://github.com/ACL4SSR/ACL4SSR</b>

    此项目Fork自fancyss

    由于原项目已停止更新Mips架构的ssr，故开坑对其进行简单维护。本人小白，并不能保证可以第一时间解决所有问题，请各位谅解！

    如果各位发现任何Bug/问题，或是有大佬愿意指点，欢迎提交Issues反馈！

    ## 初次安装/无法在线更新时请使用如下方式手动更新：

    0. 请确保安装 shadowsocks 之前，路由器已打开jffs分区，并已安装Koolshare软件中心

    1. 由于 raw.githubusercontent.com 已被DNS污染，需要手动下载 shadowsocks.tar.gz

    2. 使用WinSCP等软件将 shadowsocks.tar.gz 上传到路由器 /tmp 目录下

    3. SSH连接路由器，逐行执行以下命令

    <pre>
    tar -zxvf /tmp/shadowsocks.tar.gz
    chmod +x /tmp/shadowsocks/install.sh
    sh /tmp/shadowsocks/install.sh
    reboot
    </pre>