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

- ### [PearPC](http://pearpc.sourceforge.net/)

PearPC是一个在PC平台上独立模拟PowerPC中Mac OS、Apple Darwin及Linux软体，它遵循GPL，可以运行于基于X86平台上的Windows、Linux，以及Intel架构的Mac OS X。[1]它的第一官方版本于2004年5月10日释出。

PearPC拥有一个可以动态转换PPC代码到x86代码并进行高速缓存的“运行时编译执行”（JIT，Just-In-Time）技术处理器模拟核心。尽管只涉及x86主机体系机构，JIT模拟核心至少比体系结构独立的普通处理器模拟内核快十倍，这是完成可用的实时模拟的关键。

Win 下载地址：https://pan.baidu.com/s/1kn2fl9ojESafuXmcFkP_0w

- ### [QEMU](https://www.qemu.org/)

QEMU（quick emulator）是一款由法布里斯·贝拉（Fabrice Bellard）等人编写的免费的可执行硬件虚拟化的（hardware virtualization）开源托管虚拟机（VMM）。

其与Bochs，PearPC类似，但拥有高速（配合KVM），跨平台的特性。

QEMU是一个托管的虚拟机镜像，它通过动态的二进制转换，模拟CPU，并且提供一组设备模型，使它能够运行多种未修改的客户机OS，可以通过与KVM一起使用进而接近本地速度运行虚拟机（接近真实电脑的速度）。

QEMU还可以为user-level的进程执行CPU仿真，进而允许了为一种架构编译的程序在另外一种架构上面运行（借由VMM的形式）。

Win 下载地址：https://pan.baidu.com/s/15qfv7MkI8ugDTVr8zeCfuA

Mac 从 Homebrew 安装 ：```brew install qemu```

Mac 从 MacPorts 安装 ：```sudo port install qemu```

Linux 安装：

Arch: `pacman -S qemu`

Debian/Ubuntu: `apt-get install qemu`

Fedora: `dnf install @virtualization`

Gentoo: `emerge --ask app-emulation/qemu`

RHEL/CentOS: `yum install qemu-kvm`

SUSE: `zypper install qemu`

- ### [Xen](https://xenproject.org/)

Xen是一个开源的可直接运行于硬件层之上的虚拟化软件,它可在传统虚拟技术极度不友好的X86架构上也有上佳的表现它是英国剑桥大学开发的开源虚拟化软件,它的初衷是在一台物理机上运行上百台虚拟机;
         
Xen的设计十分精巧,它属于虚拟化type-I ,因为Xen实际是一个简化版的Hypervisor层;相对于Type-II类型的基于Host的虚拟化(如:VMware Workstattion),其性能相对会较好;Xen仅对CPU和Memory直接接管，而其它IO硬件驱动则由其上运行的第一个虚拟机来提供支持.这样做的原因是: Xen无法为众多IO设备开发驱动,而硬件设备的开发商也不会专为Xen提供驱动,因此Xen采用了这样一种特别的设计方式。

- ### [VMware Workstation Pro](https://www.vmware.com/cn.html)

VMware Workstation是VMware公司推出的一款桌面虚拟计算软件。此软件可以提供虚拟机功能，使计算机可以同时运行多个不同操作系统，以及进行开发、测试 、部署新的应用程序的最佳解决方案。该软件具有Windows、Linux版本。VMware Workstation可在一部实体机器上模拟完整的网络环境，以及可便于携带的虚拟机器，其更好的灵活性与先进的技术胜过了市面上其他的虚拟计算机软件。对于企业的 IT开发人员和系统管理员而言， VMware在虚拟网路，实时快照，拖曳共享文件夹，支持 PXE 等方面的特点使它成为必不可少的工具。

Win 下载地址：https://pan.baidu.com/s/1kdFEFD_sljhbfbPw9mibOQ

Linux 下载地址：https://pan.baidu.com/s/1nLya-sqPkffgFIflVijy6g

## ⛵编译器（提取码：1024 ）

- ### [GCC编译器](https://gcc.gnu.org/)

GCC 是開放原始碼 (open source) 的跨平台編譯器 (compiler) ，支援編譯 C 、 C++ 、 Objective-C 、 Fortran 、 Ada 及 Go 等程式語言

Win 安装包：https://pan.baidu.com/s/1EORzRJ6WwaoHnQpHNKxvdQ

- ### g++

g++是GNU组织开发出的编译器软件集合（GCC）下的一个C++编译器。它是Unix 和 Linux  系统下标配的 基于命令行的 C++编译器。如果你的系统是Windows，可以按照下面的教程安装g++。

win 安装教程：https://www.cnblogs.com/xiaolantian/p/10746206.html

安装包：https://pan.baidu.com/s/19lkCrn7zO-03L-6LijxO6Q

- ARMCC
- IAR
- LLVM
- IL2CPP 交叉编译器
- Watcom C/C++
- Tiny C Compiler（TCC）
- MinGW

## 🚧编辑器

- ### [Netbeans](https://netbeans.org/features/cpp/index.html)

Netbeans 是一个自由而开源的、流行的跨平台 IDE ，可用于 C/C++ 以及其他编程语言，可以使用由社区开发的插件展现了其完全的扩展性。

它包含了用于 C/C++ 开发的项目类型和模版，并且你可以使用静态和动态函数库来构建应用程序。此外，你可以利用现有的代码去创造你的工程，并且也可以通过拖放的方式导入二进制文件来从头构建应用。

让我们来看看关于它的特性：

```
  1. C/C++ 编辑器很好的整合了多线程的 GNU GDB 调试工具
  2. 支持代码协助
  3. 支持 C++11 标准
  4. 在里面创建和运行 C/C++ 测试程序
  5. 支持QT工具包
  6. 支持将已编译的应用程序自动打包到 .tar，.zip 等归档文件
  7. 支持多个编译器，例如： GNU、Clang/LLVM、Cygwin、Oracle Solaris Studio 和 MinGW
  8. 支持远程开发
  9. 文件导航
  10. 源代码检查
```
- ### [Code::Blocks](http://www.codeblocks.org)

Code::Blocks 是一个免费的、具有高度扩展性的、并且可以配置的跨平台 C++ IDE，它为用户提供了必备而典范的功能。它具有一致的界面和体验。

最重要的是，你可以通过用户开发的插件扩展它的功能，一些插件是随同 Code::Blocks 发布的，而另外一些则不是，它们由 Code::Block 开发团队之外的个人用户所编写的。

其功能分为编译器、调试器、界面功能，它们包括：

```
  1. 支持多种编译器如　GCC、clang、Borland C++ 5.5、digital mars 等等
  2. 非常快，不需要 makefile
  3. 支持多个目标平台的项目
  4. 支持将项目组合起来的工作空间
  5. GNU GDB 接口
  6. 支持完整的断点功能，包括代码断点，数据断点，断点条件等等
  7. 显示本地函数的符号和参数
  8. 用户内存导出和语法高亮显示
  9. 可自定义、可扩展的界面以及许多其他的的功能，包括那些用户开发的插件添加功能
```

- ### [Eclipse](http://www.codeblocks.org)

Eclipse 在编程界是一款著名的、开源的、跨平台的 IDE。它给用户提供了一个很棒的界面，并支持拖拽功能以方便界面元素的布置。

Eclipse CDT 是一个基于 Eclipse 主平台的项目，它提供了一个完整功能的 C/C++ IDE，并具有以下功能：

```
  1. 支持项目创建
  2. 管理各种工具链的构建
  3. 标准的 make 构建
  4. 源代码导航
  5. 一些知识工具，如调用图、类型分级结构，内置浏览器，宏定义浏览器
  6. 支持语法高亮的代码编辑器
  7. 支持代码折叠和超链接导航
  8. 代码重构与代码生成
  9. 可视化调试存储器、寄存器的工具
  10. 反汇编查看器以及更多功能
```

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


