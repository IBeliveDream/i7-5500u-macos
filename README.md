# i7-5500u-macos
## 先总结：将就能用，显卡，网卡，声卡，触摸板，基本上硬件都不好用。
联想小新v4000 黑苹果efi 注意屏蔽独显，镜像使用黑果小兵的macos 15.7
链接
https://blog.daliansky.net/WeChat-First-macOS-Catalina-10.15.7-19H2-official-version-Clover-5122-OC-WEPE-supports-both-INTEL-and-AMD-original-images.html
64g u盘 安装的 macOS Catalina 10.15.7(19H15) Installer for Clover 5126 and OC 0.6.3 and PE 32G

镜像 https://cloud.189.cn/t/ZJRbYzFrIRZz（访问码：f88h）
https://cloud.189.cn/t/7ZveuuuYfIjm（访问码：cx5x）
，
目前碰到的问题， 
* 1.板载网卡，无论有线还是无线全部无效， 
* 2.苹果id登录不上苹果商店（无法在商店下载）， 
* 3.装完系统后进入系统的时候有时候进不去系统，出现黑屏（屏幕是亮的），强制重启一下就好了（也可以等好像好久自动重启了），
* 4.usb可以用，但是想要联网（使用手机的usb网络共享）需要下载 瑞昱的驱动 地址 http://www.comfast.cn/index.php?m=content&c=index&a=show&catid=30&id=213 好像是这个解决了usb驱动（自带的蓝牙驱动也好用了），usb外接无线网卡（网上最便宜的usb网卡可以用，型号忘记了【当时在windows电脑好像也下载过网卡驱动的，但是苹果系统直接驱动成功】），手机usb网络共享好用，蓝牙网络可以用（慢）。
* 5. 声音输出没啥问题，录音有电流杂音。
* 6.触摸板可以滑动，点动，但是用双指弄一下就不能用了。


--------[ 鲁大师 ]----------------------------------------------------------------------------------

  软件：                 鲁大师 6.1020.3045.1228
  时间：                 2021-01-04 10:50:01
  软件：                 http://www.ludashi.com

--------[ 概览 ]----------------------------------------------------------------------------------

  电脑型号               联想 Lenovo 小新 V4000 笔记本电脑
  操作系统               Windows 10 64位（Version 1909 / DirectX 12）

  处理器                 英特尔 Core i7-5500U @ 2.40GHz 双核
  主板                   联想 XiaoXin V（5th Generation Intel Core Premium SKU - 9CC3 笔记本芯片组）
  显卡                   AMD Radeon  R9 M375 ( 2 GB )
  内存                   16 GB ( 海力士 DDR3L 1600MHz )  【原来8g，自己买的8g内存条扩展】 {拼多多}
  主硬盘                  UNIC2 S100-480 ( 480 GB / 固态硬盘 ) 【自己加的紫光s100 480固态】（京东）
  显示器                 友达 AUO38ED ( 15.5 英寸  )
  声卡                   瑞昱  @ 英特尔 High Definition Audio Controller
  网卡                   瑞昱 RTL8168/8111/8112 Gigabit Ethernet Controller / 联想

--------[ 主板 ]----------------------------------------------------------------------------------

  主板型号               联想 XiaoXin V
  芯片组                 5th Generation Intel Core Premium SKU - 9CC3 笔记本芯片组
  序列号                 MP11VQ6W
  主板版本               SDK0K09938 WIN
  BIOS                   联想 C2CN19WW(V2.00)  /  BIOS程序发布日期: 07/14/2015
  BIOS的大小             6144 KB

--------[ 处理器 ]----------------------------------------------------------------------------------

  处理器                 英特尔 Core i7-5500U @ 2.40GHz 双核
  速度                   2.40 GHz
  处理器数量             核心数：2 / 线程数：4
  核心代号               Broadwell
  生产工艺               14 nm
  插槽/插座              Socket BGA1168
  一级数据缓存           2 x 32 KB, 8-Way, 64 byte lines
  一级代码缓存           2 x 32 KB, 8-Way, 64 byte lines
  二级缓存               2 x 256 KB, 8-Way, 64 byte lines
  三级缓存               4 MB, 16-Way, 64 byte lines
  特征                   MMX, SSE, SSE2, SSE3, SSSE3, SSE4.1, SSE4.2, HTT, EM64T, EIST, Turbo Boost

--------[ 硬盘 ]----------------------------------------------------------------------------------

  产品                   UNIC2 S100-480 (固态硬盘)
  大小                   480 GB
  固件                   7E101
  接口                   SATA III
  数据传输率             600.00 MB/秒
  特性                   S.M.A.R.T,  48-bit LBA,  NCQ
  硬盘已使用             共 488 次，累计 478 小时

  产品                   希捷 ST1000LM024 HN-M101MBB 【普通便宜的硬盘支架不好用，使用的翼佳的硬盘支架】{拼多多}
  大小                   1 TB
  固件                   2BA30001
  缓存                   8 MB
  接口                   SATA II
  数据传输率             300.00 MB/秒
  特性                   S.M.A.R.T,  APM,  48-bit LBA,  NCQ
  硬盘已使用             共 1820 次，累计 3250 小时
  转速                   5400 转/分

  产品                   台电  CoolFlash USB3.1 USB Device 【做苹果盘的u盘】（拼多多 3.0）
  大小                   63 GB
  固件                   1100
  特性                   S.M.A.R.T

--------[ 内存 ]----------------------------------------------------------------------------------

  ChannelA-DIMM0         海力士 DDR3L 1600MHz 8GB
  制造日期               2015 年 49 周
  型号                   HMT41GS6BFR8A-PB
  序列号                 0D606BB1
  厂商                   Hynix
  模块位宽               64 Bits
  模块电压               SSTL 1.35V

  ChannelB-DIMM0         海力士 DDR3L 1600MHz 8GB
  制造日期               2019 年 50 周
  型号                   HMT41GS6MFR8C-PB
  序列号                 291DE7C7
  厂商                   Hynix
  模块位宽               64 Bits
  模块电压               SSTL 1.35V

--------[ 显卡 ]----------------------------------------------------------------------------------

  主显卡                 AMD Radeon  R9 M375 【这个东西要屏蔽，不然黑苹果装完后，启动的时候系统一直奔溃】
  显存                   2 GB
  频率                   核心: 1015MHz / 显存: 900MHz
  芯片制造商             AMD
  驱动版本               26.20.15019.19000
  驱动日期               20200228

  显卡                   英特尔 HD Graphics 5500
  显存                   128 MB
  显卡制造商             联想
  芯片制造商             Intel
  驱动版本               20.19.15.4624
  驱动日期               20170308

--------[ 显示器 ]----------------------------------------------------------------------------------

  产品                   友达 AUO38ED
  厂商                   友达
  固件程序日期           2014 年 43 周
  屏幕尺寸               15.5 英寸 (344 毫米 x 193 毫米)
  显示比例               宽屏 16 : 9
  分辨率                 1920 x 1080 32 位真彩色
  Gamma                  2.20

--------[ 其他设备 ]----------------------------------------------------------------------------------

  网卡                   Realtek PCIe GBE Family Controller #2

  网卡                   Intel(R) Dual Band Wireless-AC 3160 #2

  声卡                   瑞昱  @ 英特尔 High Definition Audio Controller

  键盘                   PS/2 标准键盘
  鼠标                   HID-compliant 鼠标
  鼠标                   联想 指点杆
