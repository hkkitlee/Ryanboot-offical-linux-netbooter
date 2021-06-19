# Ryanboot-offical-linux-netbooter
## Part of Ryanboot: Netboot from Linux Distribution 網絡啟動官版Linux

* 下載：[主機下載](https://hkkitlee.ddns.net:9000/ryan.zip) [備用下載](http://hkkitlee.ddns.net:8999/ryan.zip) [Github](https://github.com/hkkitlee/Ryanboot/raw/main/ryan.zip) [Gitee](https://gitee.com/hkkitlee/Ryanboot/raw/main/ryan.zip) [SourceForge](https://sourceforge.net/projects/ryanboot/files/ryan.zip/download) [mirror0](http://183.230.23.18:58000/ryanboot/ryan.zip)
* Map:[Github](https://github.com/hkkitlee/Ryanboot/blob/main/map) [Gitee](https://gitee.com/hkkitlee/Ryanboot/blob/main/map)
* Changlog:[Github](https://github.com/hkkitlee/Ryanboot/blob/main/changelog) [Gitee](https://gitee.com/hkkitlee/Ryanboot/blob/main/changelog)

### Selection/可選項：
* Mirror 鏡像源 [SourceForge](https://sourceforge.net/projects/ryanboot/files/) [mirror0](http://183.230.23.18:58000/ryanboot/)
* Release 釋放版
* Version 版本
* Manual Kernel Parameter 手動核心參數
* TUI/GUI 文字/圖像介面
* Arch detection i386/amd64 架構自動偵測

### Howto:
Ryanboot:[Github](https://github.com/hkkitlee/Ryanboot) [Gitee](https://gitee.com/hkkitlee/Ryanboot)

or

Online compile (enable https)，在線編譯「選https功能」：[rom-o-matic](https://rom-o-matic.dev/)

or
```
#!ipxe
dhcp
goto start
:start
chain --autofree https://github.com/hkkitlee/Ryanboot/raw/main/chain.ipxe || chain --autofree https://gitee.com/hkkitlee/Ryanboot/raw/main/chain.ipxe || chain --autofree http://hkkitlee.ddns.net:8999/chain.ipxe || goto start
```

or
```
#!ipxe
dhcp
goto start
:start
chain --autofree https://github.com/hkkitlee/Ryanboot-offical-linux-netbooter/raw/main/oln.ipxe || chain --autofree https://gitee.com/hkkitlee/Ryanboot-offical-linux-netbooter/raw/main/oln.ipxe || goto start
```
