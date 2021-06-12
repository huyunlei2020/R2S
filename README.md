固件发布地址：

https://github.com/a0575/Nanopi/releases

基于原生 OpenWrt 21.02 编译，默认管理地址：192.168.2.1（注意：2021-06-12之前为192.168.1.1）

同时支持 SFE/Software Offload （选则其一开启，默认开启Software Offload）

内置升级功能可用，物理 Reset 按键可用

预配置了部分插件（包括但不限于 DNS 套娃，使用时先将 SSRP 的 DNS 上游提前选成本机5335端口，然后再 ADG 中勾上启用就好*“管理账户root，密码admin”，如果要作用于路由器本身，可以把lan和wan的dns都配置成127.0.0.1，dhcp高级里设置下发dns 6,192.168.1.1。注：这里取决于你设定的路由的ip地址）

正式 Release 版本将具有可无脑 opkg kmod 的特性

R2S核心频率1.6（交换了LAN WAN），R4S核心频率2.2/1.8（建议使用5v4a电源）
