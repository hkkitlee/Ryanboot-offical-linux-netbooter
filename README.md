# Ryanboot-offical-linux-netbooter
## Part of Ryanboot: Netboot from Linux Distribution 網絡啟動官版Linux

* Map:[Github](https://github.com/hkkitlee/Ryanboot/blob/main/map) [Gitee](https://gitee.com/hkkitlee/Ryanboot/blob/main/map)
* Changlog:[Github](https://github.com/hkkitlee/Ryanboot/blob/main/changelog) [Gitee](https://gitee.com/hkkitlee/Ryanboot/blob/main/changelog)

### Selection/可選項：
* Mirror 鏡像源
* Release 釋放版
* Version 版本
* Manual Kernel Parameter 手動核心參數
* TUI/GUI 文字/圖像介面
* Arch detection i386/amd64 架構自動偵測

### Howto:
Ryanboot:[Github](https://github.com/hkkitlee/Ryanboot) [Gitee](https://gitee.com/hkkitlee/Ryanboot)

or
```#!ipxe
dhcp
goto start
:start
chain --autofree https://github.com/hkkitlee/Ryanboot/raw/main/chain.ipxe ||
chain --autofree https://gitee.com/hkkitlee/Ryanboot/raw/main/chain.ipxe ||
chain --autofree http://hkkitlee.ddns.net:8999/chain.ipxe ||
goto start```

or
```#!ipxe
dhcp
goto start
:start
chain --autofree https://raw.githubusercontent.com/hkkitlee/Ryanboot-offical-linux-netbooter/main/oln.ipxe || chain --autofree https://gitee.com/hkkitlee/Ryanboot-offical-linux-netbooter/raw/main/oln.ipxe || goto start```
