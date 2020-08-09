自用在线编译L大Openwrt固件的脚本
=

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

默认编译后的固件适用x64平台，本人使用于Esxi7.0中，配合pfsense做旁路由

使用方法
=
1.点击Fork

2.修改.config文件为自用配置文件或保持不变继续以下步骤

3.点击Star

4.如需进入menuconfig界面更改配置，待编译到 SSH connection to Actions，用浏览器打开https的网址，进入到黑屏后按 Ctrl+C ，然后输入 `cd openwrt && make menuconfig`，自行选择

5.保存修改后，回到终端界面，按 Ctrl+D 退出终端

6.Actions 自动继续进行下一步，直到编译完成

7.进入Actions的任务中下载编译好的压缩包

8.如需再次编译，点击Unstar后，再点击Star即可


已选配置
=
1.ipv6

2.frps

3.frpc

4.upnp

5.动态DNS

6.KMS服务器

7.SSR Plus+（节点仅支持SSR和Trojan）

8.解锁网易云灰色歌曲

9.广告屏蔽大师 Plus+

10.上网时间控制

11.IPSec VPN 服务器

12.主题中添加argon主题

13.添加open-vm-tools

感谢
=
参考自：https://github.com/P3TERX/Actions-OpenWrt
