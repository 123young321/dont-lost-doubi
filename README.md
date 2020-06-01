# 一个逗比写的逗比脚本

![GitHub](https://img.shields.io/github/license/mashape/apistatus.svg)
[![GitHub stars](https://img.shields.io/github/stars/ToyoDAdoubi/doubi.svg?style=popout&label=Stars)](https://github.com/ToyoDAdoubi/doubi/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ToyoDAdoubi/doubi.svg?style=popout&label=Fork)](https://github.com/ToyoDAdoubi/doubi/fork)
## 脚本索引

* [***代理相关***](#代理相关)
  * [brook.sh](#brooksh)
  * [daze.sh](#dazesh)
  * [goflyway.sh](#goflywaysh)
  * [lightsocks.sh](#lightsockssh)
  * [mtproxy.sh](#mtproxysh)
  * [mtproxy_go.sh](#mtproxy_gosh)
  * [shadowsocks python/Go/libev/R](https://githubt.com/teddysun/shadowsocks_install/)
  * ~[ss-go.sh](#ss_gosh)~
  * ~[ssr.sh](#ssrsh)~
  * [ssrmu.sh](#ssrmush)
* [***中转相关***](#中转相关)
  * [brook-pf.sh](#brook-pfsh)
  * [haproxy.sh](#haproxysh)
  * [iptables-pf.sh](#iptables-pfsh)
  * [socat.sh](#socatsh)
  * [tinymapper.sh](#tinymappersh)
* [***BT下载相关***](#bt下载相关)
  * [aria2.sh](#aria2sh)
  * [cloudt.sh](#cloudtsh)
  * [pserver.sh](#pserversh)
* [***服务器相关***](#服务器相关)
  * [bbr.sh](#bbrsh)
  * [ban_iptables.sh](#ban_iptablessh)
  * [status.sh](#statussh)
  * [ssh_port.sh](#ssh_portsh)
* [***VPN 相关***](#vpn相关)
  * [ocserv.sh](#ocservsh)
* [***DNS 相关***](#dns相关)
  * [dowsdns.sh](#dowsdnssh)
* [***HTTP 相关***](#http相关)
  * [caddy_install.sh](#caddy_installsh)
  * [pythonhttp.sh](#pythonhttpsh)
* [***其他***](#其他)
  * [adbyby.sh](#adbybysh)
  * [gfw_push.sh](#gfw_pushsh)
  * [libsodium.sh](#libsodiumsh)
  * [ssrstatus.sh](#ssrstatussh)
  * [ssr_check.sh](#ssr_checksh)
  * [ssr_ip_check.sh](#ssr_ip_checksh)
* [***反垃圾邮件 BT Pt***](#反垃圾邮件BTPT)
    * [Get_Out_Spam.sh](#Get_Out_Spam)

---

## 代理相关

~## ss_go.sh~

- 脚本说明: [hadowsocks 一键安装管理脚本](https://doubibackup.com/kd691l4o.html)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 项目地址: https://github.com/shadowsocks/go-shadowsocks2

#### 脚本特点:
目前网上的各个Shadowsocks脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

---
~## ssr.sh~

- 脚本说明: [hadowsocksR 一键安装管理脚本，支持单端口/多端口切换和管理](https://doubibackup.com/z2a4lk3l.html)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 项目地址: https://github.com/ToyoDAdoubiBackup/shadowsocksr

#### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 端口设备数
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 切换管理 单/多端口
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

---
## ssrmu.sh

- 脚本说明: [hadowsocksR 一键安装管理脚本，支持流量控制]( https://doub.io/ss-jc60/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 项目地址: https://github.com/ToyoDAdoubiBackup/shadowsocksr
## shadowsocks python/Go/libev/R
-脚本说明:Shadowsocks Python/Go/Libev/R 一键安装脚本（四合一）shadowsocks-all.sh
-系统说明
-使用方法：
-项目地址[teddysun/shadowsocks_install](https://github.com/teddysun/shadowsocks_install/tree/master)

#### 脚本特点:
目前网上的各个ShadowsocksR脚本基本都是只有 安装/启动/重启 等基础功能，对于小白来说还是不够简单方便。既然是一键脚本，那么就要尽可能地简单，小白更容易接受使用！

- 支持 限制 用户速度
- 支持 限制 用户设备数
- 支持 限制 用户总流量
- 支持 定时 流量清零
- 支持 显示 当前连接IP
- 支持 显示 SS/SSR连接+二维码
- 支持 一键安装 锐速
- 支持 一键安装 BBR
- 支持 一键封禁 垃圾邮件(SMAP)/BT/PT

---
## brook.sh

- 脚本说明: [『原创』一个优秀的跨平台 Socks5代理软件 —— Brook 一键安装管理脚本](https://doubibackup.com/aybh4ww5-2.html)
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 项目地址:[Brook](https://github.com/txthinking/brook)

#### 对于Windows的用户，最新版本的文件我是的有[Brook.msi文件安装时，出现闪退](https://github.com/txthinking/brook/releases/download/v20200502/Brook.msi),这里需要安装之前发布的低版本的软件，比如[Brook.exe(70M的)](https://github.com/txthinking/brook/releases/download/v20190205/Brook.exe)
如果这个也不行，可以使用[Brook-Widows-386](https://github.com/txthinking/brook/releases/download/v20200502/brook_windows_386.exe)配合着逗比的[Brook Tool](https://tok9.com/archives/233/)也可以使用 ####

---
## goflyway.sh

- 脚本说明: GoFlyway 一键安装管理脚本
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/goflyway-jc2/


---
## lightsocks.sh

- 脚本说明: [『原创』更方便的Windows系统 Lightsocks 客户端 —— Lightsocks Tools](https://doubibackup.com/_8lmsikm.html)
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法:
#### Windows版尝试用[Windows-amd64]()，但是不工作。你可以用[Lightsocks Tools](https://soft.l-t.top/DOUBI_Soft/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91/PC/Lightsocks/Lightsocks%20Tools/)，
配合Windows-amd64一块使用，类似于Brook Tools。

---
## daze.sh

- 脚本说明: [AZE 一键安装管理脚本](https://doub.io/daze-jc3/)
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+


---
## mtproxy.sh

- 脚本说明: [tproto Proxy 一键安装管理脚本](tps://doub.io/shell-jc7/)
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+
- 使用方法: 

---
## mtproxy_go.sh

- 脚本说明: [tproto Proxy Go版 一键安装管理脚本](https://doub.io/shell-jc9/)
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+
- 使用方法: 

---

## 中转相关

## iptables-pf.sh

- 脚本说明: [iptables 端口转发 一键安装管理脚本](https://doubibackup.com/mbofzp9h-2.html)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

---
## brook-pf.sh

- 脚本说明: Brook 端口转发 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-37/
---
## haproxy.sh

- 脚本说明: HaProxy 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-19/
---
## socat.sh

- 脚本说明: Socat 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-18/
---
## tinymapper.sh

- 脚本说明: tinyPortMapper 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-36/

---

## BT下载相关

## aria2.sh

- 脚本说明: [BT/种子/磁力链接/HTTP/FTP 离线下载工具 —— Aria2 新 手动安装教程](https://doubibackup.com/bizht36j-3.html)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

---
## cloudt.sh

- 脚本说明: [loud Torrent 一键安装管理脚本](https://doub.io/wlzy-12/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 项目地址: https://github.com/jpillora/cloud-torrent
---
## pserver.sh

- 脚本说明: [eerflix Server 一键安装管理脚本](https://doub.io/wlzy-13/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/wlzy-13/
- 项目地址: https://github.com/asapach/peerflix-server
---

## 服务器相关

## bbr.sh

- 脚本说明: [BBR 一键安装管理脚本](https://doub.io/wlzy-16/)
- 系统支持: Debian6+ / Ubuntu14+

---
## status.sh

- 脚本说明: [ServerStatus 一键安装管理脚本](https://doub.io/shell-jc3/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: 

---
## ban_iptables.sh

- 脚本说明: iptables 垃圾邮件(SPAM)/BT/PT 一键封禁脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc2/

---
## ssh_port.sh

- 脚本说明: SSH 一键修改端口脚本
- 系统支持: Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/linux-jc11/
---

## VPN相关

## ocserv.sh

- 脚本说明: Ocserv AnyConnect 一键安装管理脚本
- 系统支持: Debian7+ / Ubuntu14+
- 使用方法: https://doub.io/vpnzy-7/
---

## DNS相关

## dowsdns.sh

- 脚本说明: [DowsDNS 一键安装管理脚本](https://doub.io/dowsdns-jc3/)
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+

---

## HTTP相关

## caddy_install.sh

- 脚本说明: [Caddy 一键安装脚本](https://doub.io/shell-jc1)
- 系统支持: CentOS6+ / Debian7+ / Ubuntu14+



#### 下载安装:
``` bash
git clone https://github.com/handsomego/doubi  && cd doubi && chmod +x caddy_install.sh && bash caddy_install.sh
 # 安装插件：
 bash caddy_install.sh xxx,xxx
  # 例如同时安装 http.filemanager 和 http.webdav插件：
  bash caddy_install.sh http.filemanager,http.webdav
  # 插件和Caddy是集成在一起的(单个二进制文件)，多个插件必须同时安装。
# 卸载命令：
caddy_install.sh uninstall
```

---
## pythonhttp.sh

- 脚本说明: [SimpleHTTPServer 一键安装管理脚本](https://doub.io/wlzy-8/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

---

## 其他

## adbyby.sh

- 脚本说明: ADbyby 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/adbyby-jc2/


## gfw_push.sh

- 脚本说明: 监测服务器IP是否被墙并推送至 Telegram 一键脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc8/

---
## libsodium.sh

- 脚本说明: libsodium 一键安装管理脚本
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: https://doub.io/shell-jc6/

---
## ssr_check.sh

- 脚本说明: [ShadowsocksR 批量快速验证账号可用性](https://doub.io/ss-jc56/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: 

---
## ssrstatus.sh

- 脚本说明: [ShadowsocksR 账号在线监控网站](https://doub.io/shell-jc5/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+
- 使用方法: 

---
## ssr_ip_check.sh

- 脚本说明: [ShadowsocksR 检测每个端口链接IP数](https://doub.io/ss-jc50/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

---
## ~~pipes.sh~~

- 脚本说明: [PipeSocks 一键安装管理脚本（该软件已停更）](https://doub.io/pipesocks-jc2/)
- 系统支持: CentOS7 / Debian7+ / Ubuntu14+


## ~~gogo.sh~~

- 脚本说明: [GoGo Tunnel 一键安装管理脚本（该软件已停更）](https://doub.io/wlzy-24/)
- 系统支持: CentOS6+ / Debian6+ / Ubuntu14+

---
## 发垃圾邮件,BT,PT

## Get_Out_Spam.sh
- 操作说明: [Get_Out_Spam Linux中利用 iptables 封垃圾邮件(SPAM)和BT(磁力链接)、PT](https://doubibackup.com/wkcjzpyd-4.html)
- 操作系统：暂时没测试，（各Linux系统应该都可以搭建）

---
Copyright (C) 2016-2018 Toyo <https://doubibackup.com>
