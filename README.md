# SSR for mips router with merlin koolshare firmware
* <b>原项目：https://github.com/harry3633/fancyss/tree/master/fancyss_mipsel</b>
* <b>此项目仅用于merlin koolshare mipsel架构改版固件</b>

此项目Fork自fancyss

由于原项目已停止更新Mips架构的ssr，故开坑对其进行简单维护。本人小白，并不能保证可以第一时间解决所有问题，请各位谅解！

如果各位发现任何Bug/问题，或是有大佬愿意指点，欢迎提交Issues反馈！

初次安装/无法在线更新时请使用如下方式手动更新：
<pre>
wget --no-check-certificate --timeout=15 -P /tmp https://github.com/Magic-Xin/ssr_mips/blob/master/shadowsocks.tar.gz
tar -zxvf /tmp/shadowsocks.tar.gz
chmod +x /tmp/shadowsocks/install.sh
sh /tmp/shadowsocks/install.sh
</pre>