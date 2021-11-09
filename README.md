# 🤸‍♀️🤾‍♀️🤸‍♂️硬核总结linux环境开发工具，包含linux，虚拟机，编译器，编辑器，测试工具，加密工具

## 🚩源码(提取码1024)

- [linux-5.15(最新版本).tar](https://pan.baidu.com/s/1cRp-cH7Cmn9AWmxtIKetxw)
- [linux-5.13.5(稳定版).tar](https://pan.baidu.com/s/1HNYQ6UktSU5UxRVWZEELHg)
- [linux-5.10.53(长期版).tar](https://pan.baidu.com/s/1yLIRgxPrbmYGw1JLXWNjkg)
- [linux-5.4.135（长期版）.tar](https://pan.baidu.com/s/18r4Rt8jNnBK9nsARLMWs_A)
- [linux-4.19.198（长期版）.tar](https://pan.baidu.com/s/1I1wrVUshb855G7v7dhGBpA)
- [linux-4.14.240（长期版）.tar](https://pan.baidu.com/s/1ZHoEubSFZ0JFH2uV6WK6Rg)
- [linux-4.12(长期版).tar](https://pan.baidu.com/s/1bLpchNMkYXMYjspqen0MOw)
- [linux-4.9.276（长期版）.tar](https://pan.baidu.com/s/1k43C6q5ckiweyvWC9kkxkw)
- [linux-4.4.276（长期版）.tar](https://pan.baidu.com/s/1NvTBB-zPwrmaUYIb6i9ERA)

## 🏳‍🌈虚拟机（提取码：1024 ）

- ### [Bochs](https://bochs.sourceforge.io/)

 Bochs 是一个高度便携的开源 IA-32 (x86) PC 仿真器，用 C++ 编写，可在大多数流行平台上运行。它包括对 Intel x86 CPU 的仿真、通用 I/O 设备和自定义 BIOS。
 
- ### [DOSBox](https://www.dosbox.com/)

是一款免费、开源的模拟器，用于运行适用MS-DOS兼容操作系统的软件（主要是电子游戏）。它的最初版本于2002年发布。

DOSBox支持许多IBM PC兼容的显卡和声卡，为本地的DOS程序提供执行环境，使这些程序可以正常运行于大多数现代计算机上的不同操作系统。DOSBox主要以C++编写，是以GNU通用公共许可证许可发布的自由软件。

DOSBox所运行的MS-DOS软件通常不能在现代计算机上直接运行，它们通常与现代的主流硬件和操作系统不兼容。DOSBox在模拟MS-DOS同时，还增加了一些可用特性，包括虚拟磁盘、点对点网络、对模拟画面截图和录像。有些非官方的DOSBox变体，如DOSBox SVN Daum和DOSBox SVN-lfn提供了更多的功能，比如存档、长文件名支持等[4]。有些游戏开发商重新发行早期的DOS游戏时，也会使用DOSBox，使其可以在现代计算机上运行。

- ### [DOSEMU](http://www.dosemu.org/)

一个兼容层软件包，它使DOS操作系统（例如，MS-DOS、DR-DOS、FreeDOS）和应用软件能够在基于x86的 PC（IBM PC 兼容计算机）上的Linux上运行。

- ### [Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/)

代号Viridian,旧称Windows Server Virtualization，是Microsoft的本地虚拟机管理程序，它可以在运行x86-64位的Windows上创建虚拟机。[2] 从Windows 8开始，Hyper-V取代Windows Virtual PC作为Windows客户端版本的硬件虚拟化组件。可以配置运行Hyper-V的服务器计算机能够将单个虚拟机公开到一个或多个网络。Hyper-V是与Windows Server 2008一起首次发布，自Windows Server 2012和Windows 8以来一直无需额外付费。独立的Windows Hyper-V Server是免费的，但仅具有命令行接口。

- ### [KVM](https://www.linux-kvm.org/page/Main_Page)

KVM（用于基于内核的虚拟机）是适用于 x86 硬件上的 Linux 的完整虚拟化解决方案，包含虚拟化扩展（Intel VT 或 AMD-V）。它由一个可加载的内核模块 kvm.ko 组成，该模块提供核心虚拟化基础架构和一个处理器特定模块 kvm-intel.ko 或 kvm-amd.ko。

- ### [Logical Domains](https://docs.oracle.com/cd/E19053-01/ldoms.mgr11/820-4913-10/chapter1.html)

SPARC 虚拟机管理程序是一个小型固件层，它提供了一个稳定的虚拟机架构，可以在其中写入操作系统。使用管理程序的 Sun 服务器提供硬件功能来支持管理程序对逻辑操作系统活动的控制。

- ### [OpenVZ](https://openvz.org/)

OpenVZ是基于Linux内核的操作系统级虚拟化技术。OpenVZ允许物理服务器运行多个操作系统，该技术常用于虚拟专用服务器（VPS，Virtual Private Server）。

与VMware这种虚拟机和Xen这种硬件辅助虚拟化技术相比，OpenVZ的主机与客户系统都必须是Linux（虽然在不同的虚拟环境里可以用不同的Linux发行版）。但是，OpenVZ声称这样做有性能上的优势。根据OpenVZ网站的说法，使用OpenVZ与使用独立的实体服务器相比，性能只会有1-3%的损失。

OpenVZ的Linux客户系统其实是共享OpenVZ主机Linux系统的内核，也就意味着OpenVZ的Linux客户系统不能升级内核。

OpenVZ是SWsoft, Inc.公司开发的专有软件Virtuozzo（Virtuozzo虚拟机还支持Windows客户系统）的基础。OpenVZ的授权为GPLv2。

OpenVZ由两部分组成，一个经修改过的Linux内核与一套用户工具。

- ### [Oracle VM VirtualBox](https://www.virtualbox.org/)

甲骨文公司xVM虚拟化平台技术的一部分。它提供用户在32位或64位的Windows、Solaris及Linux 操作系统上虚拟其它x86的操作系统。用户可以在VirtualBox上安装并且运行Solaris、Windows、DOS、Linux、OS/2 Warp、OpenBSD及FreeBSD等系统作为客户端操作系统[1]。

与同性质的VMware及Virtual PC比较下，VirtualBox独到之处包括远程桌面协议（RDP）、iSCSI及USB的支持，VirtualBox在客户机操作系统上已可以支持USB 3.0的硬件设备，不过要安装Virtualbox Extension Pack。

Win 下载地址：https://pan.baidu.com/s/1Mj-MElyPxkllSRqUVqWXxQ

Mac 下载地址：https://pan.baidu.com/s/1Eamo0Ar03HIrZs299IpGSA

Linux 下载地址：https://pan.baidu.com/s/1M0dsBJjXhi6jy_mAjVIG2g

- ### [Parallels Workstation](https://www.parallels.com/)

由Parallels推出的一款为使用英特尔处理器的苹果电脑提供硬件虚拟化的软件。在版本16.5后也为使用Apple Silicon的苹果电脑提供x86-64架构的虚拟化。用户可以通过Parallels Desktop for Mac在苹果电脑上安装Windows、Linux发行版、FreeBSD、MS-DOS、EComStation、OS/2、Solaris等系统。

Mac 安装包：https://pan.baidu.com/s/1H2n00Dt7z9WI-Q5PqOoqkg 

- PearPC
- QEMU
- SimNow
- Sun xVM
- Xen

## ⛵编译器

- GCC编译器
- g++
- ARMCC
- IAR
- LLVM
- IL2CPP 交叉编译器
- Watcom C/C++
- Tiny C Compiler（TCC）
- MinGW

## 🚧编辑器

- Netbeans
- Code::Blocks
- Eclipse 
- CodeLite 
- Bluefish 
- Brackets
- Atom 
- Sublime Text
- JetBrains CLion
- Visual Studio Code
- KDevelop 
- Geany 
- Ajunta DevStudio 
- GNAT Programming Studio
- Qt Creator
- Emacs 
- Nano
- Vim
- Joe
- Notepad++
- Light Table

## 🌋测试工具

  
### 压力测试

- ApacheBench
- IOmeter
- webbench
- siege
- nbench
- stress
- prime
- Memtester

### 性能测试
  
- WebLOAD
- LoadUI NG Pro
- SmartMeter.io
- Tricentis Flood
- LoadView
- Apache JMeter
- LoadRunner
- Rational performance tester
- NeoLoad
- LoadNinja
- WAPT
- Loadster
- LoadImpact
- Testing Anywhere
- QEngine (ManageEngine）
- OpenSTA
- Sysbench 


