# Sonoma---Opencore-EFI

###感谢 Acidanthera 项目提供的驱动，以及一众如黑果小兵，大头蔡cass，小明和他的女朋友等大佬提供的教程
<pre>
  Sroll down for English Version.
  黑苹果 Sonoma EFI
  OpenCore 版本: 1.0.2 (Sequoia) & 0.9.8 (Sonoma) （2024年11月最后更新）
  电脑配置：    处理器 i7 - 6700
              显卡 HD530 + AsRock 幻影游戏 Radeon RX 6950XT
              内存条 金士顿DDR4 2133 Mhz
              主板 ASUS B250M-Kylin
              硬盘 西数 SN580 SSD 2TB +希捷 1TB (HDD) +东芝 2TB (HDD)
              网卡 RTL8111 + Fenvi T919 + Broadcom BCM4360
              声卡 ALC887
  能用的功能：Airplay，随航，接力，隔空投送，睡眠。
  不能用的：还没发现有
  EFI的特别之处：定制了ALC，修改了887声卡驱动参数实现更好地使用效果
               定制了USB驱动，突破15个端口的限制
  ⚠️⚠️重要！！！
        如果你没有机械硬盘，请删除CtlnaAHCIPort.kext
        使用EFI前请重新生成新的序列号
</pre>

<pre>
截图:
<img width="523" alt="image" src="https://github.com/chunma26/Sonoma---Opencore-EFI/assets/56785635/2abca978-c731-4968-b275-e63c60519c97"> 
<img width="924" alt="image" src="https://github.com/chunma26/Sonoma---Opencore-EFI/assets/56785635/83ffedfa-9bbc-4f6b-9f35-3787874b2969">
</pre>

<pre>

Hackintosh EFI for Sonoma
Version of Opencore used : 1.0.2 (Sequoia) & 0.9.8 (Sonoma) (Last edited on November 2024)

My Computer Configuration :    CPU      i7-6700
                               GPU      HD530 + AsRock Phantom Gaming Radeon RX 6950XT
                               Rom      Kingston DDR4 2133 Mhz
                          MotherBoard   ASUS B250M-KYLIN
                             Storage     Western Digital Blue SN580 SSD 2TB + Seagate HDD 1TB + Toshiba HDD 2TB
                             Network    RTL8111 + Fenvi T919 Broadcom BCM4360
                              Sound     ALC887
Work: Wi-Fi, Bluetooth, Sidecar, Airplay, Handoff, Cursor and Keyborad, AirDrop, Fully support on Sleep.
Not work: Have not found yet. :D


Special of this EFI: AppleALC.kext customized, USBPort.kext customized.
*For AppleALC.kext: Better support on ALC877 model. Use alcid 110 instead of 11
*For USBPort.kext: The limit of 15 ports is exceeded.

####  ⚠️   If you do not have a HDD drives, please romve the CtlnaAHCIPort.kext.
####       Remember to Regenerate a now Serial number

</pre>

<pre>
ScreenShot:
<img width="523" alt="image" src="https://github.com/chunma26/Sonoma---Opencore-EFI/assets/56785635/2abca978-c731-4968-b275-e63c60519c97"> 
<img width="924" alt="image" src="https://github.com/chunma26/Sonoma---Opencore-EFI/assets/56785635/83ffedfa-9bbc-4f6b-9f35-3787874b2969">
</pre>
