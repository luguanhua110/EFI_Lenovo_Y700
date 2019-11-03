Lenovo IdeaPad Y700 macOS Catalina 10.15 EFI

一、版本管理

2019.11.3  新建仓库，更新内容为： 更新 kexts 为目前最新版。

WhateverGreen.kext  1.3.4  
AppleALC.kext       1.4.3  
Lilu.kext           1.3.9  
  
  
AirportBrcmFixup.kext       2.0.4  
BrcmBluetoothInjector.kext  2.5.0  
BrcmFirmwareData.kext       2.5.0  
BrcmPatchRAM3.kext          2.5.0  
  
  
FakeSMC.kext                1800  
FakeSMC_ACPISensors.kext  
FakeSMC_CPUSensors.kext  
FakeSMC_GPUSensors.kext  
FakeSMC_LPCSensors.kext
FakeSMC_SMMSensors.kext  
   

二、硬件配置

硬件改变：  
蓝牙WIFI        已硬改为：BCM94352Z  
储存            已硬改为：Intel SSD Pro 760P 512G  
  
维持不变：  
处理器名称      Intel Core i7-6700HQ, 3300 MHz (33 x 100)  
主板名称        Lenovo ideapad Y700-15ISK  
主板芯片组      Intel Sunrise Point HM170, Intel Skylake-H  
系统内存        16211 MB (DDR4 SDRAM)  
核显           Intel(R) HD Graphics 530 (1 GB)  
声卡音频        Realtek ALC235 @ Intel Sunrise Point PCH - High Definition Audio Controller [D-1]  
HDMI          1个HDMI输入接口  
HDMI声音       Intel Skylake HDMI @ Intel Sunrise Point PCH - High Definition Audio Controller [D-1]  
USB           1个USB2  2个USB3  
Easycamer    （内建）    
读卡器         左边有 1 个读卡器，因为从来没有用过，没有检测是否可用。  

三、如何使用  
 
 3.1 删除 /EFI/CLOVER/ACPI/patched 中的DSDT.aml 因为这台电脑换过硬件，所以这个DSDT可能不适合你。    
 3.2 删除 /EFI/CLOVER/ACPI/patched 中的SSDT-NVMe.aml 。如果你没有NVMe固态硬盘。    