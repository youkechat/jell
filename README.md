## 适用于基于官方源码的19.07及以上的分支.
## 在lean源码中有些插件可能不适用,主要是network中 ifname, device 命名不同引起的.
## 所有插件都为网上收集的开源插件,感谢作者们的付出.

### 本仓库所有插件已编译IPK下载

| CPU架构           | 下载地址                                             | 适用设备    | 软件源    | 更新频率    |
|----------------|-----------------------------------------------------|--------------------------------------|-----------|-----------|
| X86_64         | [📥](https://op.supes.top/packages/x86_64/)         |          PC软路由    | 仅限 [此源码固件](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s) 使用 | 日更  |
| aarch64_generic    | [📥](https://op.supes.top/packages/aarch64_generic/)     |   R2S/R4S等        |  仅限 [此源码固件](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s) 使用 | 日更  |
| aarch64_cortex-a72    | [📥](https://op.supes.top/packages/aarch64_cortex-a72/)     |  树莓派4B等   |  仅限 [此源码固件](https://github.com/kiddin9/OpenWrt_x86-r2s-r4s) 使用  |  日更 |
| mipsel_24kc    | [📥](https://op.supes.top/packages/mipsel_24kc/)     |  k2p,ac2100等 | src/gz openwrt_kiddin9 https://op.supes.top/packages/mipsel_24kc   | 月更  |
| aarch64_cortex-a53    | [📥](https://op.supes.top/packages/aarch64_cortex-a53/) |  N1,玩客云等 |  src/gz openwrt_kiddin9 https://op.supes.top/packages/aarch64_cortex-a53 |   月更 |

### 使用软件源请删除 opkg 配置中的 option check_signature
