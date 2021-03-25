# Ryanboot-offical-linux-netbooter
Netboot from Linux Distribution 
網絡啟動官版Linux
* Map:[github](https://github.com/hkkitlee/Ryanboot/blob/main/map) [gitee](https://gitee.com/hkkitlee/Ryanboot/blob/main/map)
```
#!ipxe
dhcp && chain --autofree http://hkkitlee.ddns.net:8999/chain.ipxe
```
or
```
#!ipxe
chain https://raw.githubusercontent.com/hkkitlee/Ryanboot-offical-linux-netbooter/main/oln.ipxe || chain https://gitee.com/hkkitlee/Ryanboot-offical-linux-netbooter/raw/main/oln.ipxe
```
###Selection/可選項：
* Mirror 鏡像源
* Version 版本
* Manual Kernel Parameter 手動核心參數
* TUI/GUI 文字/圖像介面
* Arch detection 架構自動偵測

## Main:
* Ryanboot:[github](https://github.com/hkkitlee/Ryanboot) [gitee](https://gitee.com/hkkitlee/Ryanboot)
