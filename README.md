自用在线编译L大Openwrt固件的脚本
=
默认编译后的固件适用x64平台，本人使用于Esxi7.0中，配合pfsense做旁路由

使用方法
=
1.点击Fork
2.修改.config文件为自用配置文件或保持不变继续以下步骤
3.如需进入menuconfig界面更改配置，待编译到 SSH connection to Actions，用浏览器打开https的网址，进入到黑屏后按 Ctrl+C ，然后输入 `cd openwrt && make menuconfig`，自行选择
4.保存修改后，回到终端界面，按 Ctrl+D 退出终端
5.Actions 自动继续进行下一步，直到编译完成
6.进入Actions的任务中下载编译好的压缩包

已选配置
=
