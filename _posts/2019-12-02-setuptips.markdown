---
layout: post
title:  "「实用小技能之」学习环境配置"
categories: “Tips”
permalink: :/categories/:day/:month:/year
---

## 操作系统配置
### 操作系统的选择
### Linux操作系统简介
#### Linux的由来
Linux最初是于1991 年的十月，由一个名为 Linus Torvalds的年轻芬兰大学生带头开发的作业系统.Linux 是一套 Unix-like 的作业系统，是 Unix 的一种，它控制整个系统基本服务的核心程式 (kernel) 是由 Linus 带头开发出来的，Linux这个名称便是以Linus's Minix来命名，Linus 选择用大众公有版权(General Public License,GPL)的方式来发行这份程式，即Linux 实际上是免费开源的，任何个人和组织均可随心所欲的与更改 Linux 的原始程式，这一特点吸引了无数电脑高手投入开发、改善 Linux 的核心程式，使得 Linux 的功能日见强大，所以今日我们可以在网路上免费下载 Linux 使用，或者花很少的一点费用就可以取得 Linux 光碟，这都是因为 Linux 是 GPL 版权的缘故
Linux的发行版本可以大体分为两类，一类是商业公司维护的发行版本RedHat系列，另一类是社区组织维护的发行版本Debian系列. 
#### Ubuntu版本
Ubuntu严格来说不能算一个独立的发行版本，Ubuntu是基于Debian的unstable版本加强而来，可以这么说，Ubuntu就是 一个拥有Debian所有的优点，以及自己所加强的优点的近乎完美的 Linux桌面系统。根据选择的桌面系统不同，有三个版本可供选择，基于Gnome的Ubuntu，基于KDE的Kubuntu以及基于Xfc的 Xubuntu。特点是界面非常友好，容易上手，对硬件的支持非常全面，是最适合做桌面系统的Linux发行版本。
#### Deepin版本
Deepin中文翻译为深度，还记得那个win7时代的深度技术和雨林木风么。它就是由深度技术开发的Linux版本。算是国产linux系统中颜值担当。deepin系统也有很多人性化的小功能，例如自带的vim并已经具有良好的configuration，非常适合国人linux小白。商店应用也高度符合国人口味。
#### Linux系统的选择
Distrowatch发布了一份详细的linux系统清单，它给我们了以下建议：

Ubuntu、Linux Mint和MX Linux被认为是新用户最容易使用的，他们想要在不需要掌握所有复杂性的情况下，尽快在Linux中提高生产力。

Arch Linux、Gentoo和Slackware Linux是更高级的发行版，需要大量的学习才能有效地使用它们。

openSUSE、Fedora、Debian GNU/Linux可以被划分为良好的“中间道路”发行版，这些发行版通常用作其他发行版的基础。

CentOS是一个企业发行版，适合那些更喜欢稳定性、可靠性和长期支持而不是尖端功能和软件的人。

[原文地址](https://distrowatch.com/dwres.php?resource=major)



#### Linux系统下载链接

推荐使用Ubuntu操作系统

[Ubuntu系统镜像下载地址](https://www.ubuntu.com/download)

截至目前为止，网提供两个下载版本：
Ubuntu server 18.04.2LTS #此为long-term support version，长期维护版，保质期到2023年6月（推荐）
Ubuntu Server 19.04 #此为latest version，最新版，保质期相较短，到2020年一月。

[Centos系统镜像下载地址](https://www.centos.org/download/)

主要有两种版本，截至目前为止：
CentOS-7-x86_64-DVD-1810.iso #DVD版，此映像包含可以使用安装程序。这是大多数用户的推荐。
CentOS-7-x86_64-Minimal-1810.iso #基本版，所有东西都需要使用yum安装。

[Deepin系统镜像下载地址](https://www.deepin.org/download/)

### windows虚拟机的选择
模拟器常用的有vmware workstation 和 virtual box
关于两者的优劣，在网上有篇评分很高的文章，以下是其结论翻译：
VirtualBox和VMware是市场上排名前两位的虚拟化平台，这使得在这两种产品之间进行选择变得很困难。本文对VirtualBox和VMware最重要的特性进行了解释和比较，以帮助您做出最适合自己的正确选择。你可以参考以下建议:
* 如果需要免费的桌面虚拟化解决方案，可以选择VirtualBox。
* 如果需要在服务器上运行vm的免费虚拟化解决方案，请选择VirtualBox或VMware ESXi免费版。
* 如果您需要一个具有扩展3D图形支持和广泛设置列表的桌面的最终解决方案，请选择VMware Workstation(或VMware Fusion for Mac计算机)。
* 如果您需要一个免费的虚拟化解决方案，它只需要在桌面上运行VMware vm和基本选项，那么您可以选择VMware Player。
* 如果您需要最大限度地集成VMware桌面解决方案和VMware vSphere (vCenter server, ESXi hosts)，请选择VMware Workstation或VMware Fusion Pro。您可以使用VMware Workstation或Fusion Pro远程连接到vCenter Server或ESXi主机，并可以管理驻留在这些资源上的虚拟机。VMware提供了一个免费的VMware vCenter转换器，用于将工作站格式的vm转换为ESXi格式的vm(反之亦然)。
* 如果您的旧计算机的处理器不支持硬件虚拟化技术，请选择VirtualBox，它提供软件虚拟化。
* 如果您需要部署多个服务器、运行大量vm、使用集群特性等的最终企业级解决方案，请选择基于带有vCenter ESXi服务器的VMware vSphere。

VirtualBox和VMware都提供性能和高可靠性。最后的决定取决于你。评估哪些特性和优势对您的基础设施至关重要，并选择最合适的产品。如果您想了解更多关于虚拟化解决方案的信息，还可以将VirtualBox与Hyper-V进行比较。
[原文地址](https://www.nakivo.com/blog/vmware-vs-virtual-box-comprehensive-comparison/)
#### 虚拟机下载链接
推荐使用VirtualBox
[VMvare workstation 下载地址](https://my.vmware.com/web/vmware/info?slug=desktop_end_user_computing/vmware_workstation_pro/12_0)

[Virtualbox 下载地址](https://www.virtualbox.org/wiki/Downloads)

## python介绍
### Python发展历史
[原文地址](http://www.cnblogs.com/vamei)
#### 起源
Python的作者，Guido von Rossum，荷兰人。1982年，Guido从阿姆斯特丹大学获得了数学和计算机硕士学位。然而，尽管他算得上是一位数学家，但他更加享受计算机带来的乐趣。用他的话说，尽管拥有数学和计算机双料资质，他总趋向于做计算机相关的工作，并热衷于做任何和编程相关的活儿。在那个时候，Guido接触并使用过诸如Pascal、C、Fortran等语言。这些语言的基本设计原则是让机器能更快运行。

在80年代，虽然IBM和苹果已经掀起了个人电脑浪潮，但这些个人电脑的配置很低。比如早期的Macintosh，只有8MHz的CPU主频和128KB的RAM，一个大的数组就能占满内存。所有的编译器的核心是做优化，以便让程序能够运行。为了增进效率，语言也迫使程序员像计算机一样思考，以便能写出更符合机器口味的程序。在那个时代，程序员恨不得用手榨取计算机每一寸的能力。有人甚至认为C语言的指针是在浪费内存。至于动态类型，内存自动管理，面向对象…… 别想了，那会让你的电脑陷入瘫痪。这种编程方式让Guido感到苦恼。

Guido知道如何用C语言写出一个功能，但整个编写过程需要耗费大量的时间，即使他已经准确的知道了如何实现。他的另一个选择是shell。Bourne Shell作为UNIX系统的解释器已经长期存在。UNIX的管理员们常常用shell去写一些简单的脚本，以进行一些系统维护的工作，比如定期备份、文件系统管理等等。shell可以像胶水一样，将UNIX下的许多功能连接在一起。许多C语言下上百行的程序，在shell下只用几行就可以完成。然而，shell的本质是调用命令。它并不是一个真正的语言。比如说，shell没有数值型的数据类型，加法运算都很复杂。总之，shell不能全面的调动计算机的功能。Guido希望有一种语言，这种语言能够像C语言那样，能够全面调用计算机的功能接口，又可以像shell那样，可以轻松的编程。

ABC语言让Guido看到希望。ABC是由荷兰的数学和计算机研究所开发的。Guido在该研究所工作，并参与到ABC语言的开发。ABC语言以教学为目的。与当时的大部分语言不同，ABC语言的目标是“让用户感觉更好”。ABC语言希望让语言变得容易阅读，容易使用，容易记忆，容易学习，并以此来激发人们学习编程的兴趣。比如下面是一段来自Wikipedia的ABC程序，这个程序用于统计文本中出现的词的总数：
```
   HOW TO RETURN words document:
      PUT {} IN collection
      FOR line IN document:
         FOR word IN split line:
            IF word not.in collection:
               INSERT word IN collection
      RETURN collection
```
HOW TO用于定义一个函数。一个Python程序员应该很容易理解这段程序。ABC语言使用冒号和缩进来表示程序块。行 尾没有分号。for和if结构中也没有括号() 。赋值采用的是PUT，而不是更常见的等号。这些改动让ABC程序读起来像一段文字。 尽管已经具备了良好的可读性和易用性，ABC语言最终没有流行起来。

在当时，ABC语言编译器需要比较高配置的电脑才能运行。而这些电脑的使用者通常精通计算机，他们更多考虑程序的效率，而非它的学习难度。除了硬件上的困难外，ABC语言的设计也存在一些致命的问题： 可拓展性差。ABC语言不是模块化语言。如果想在ABC语言中增加功能，比如对图形化的支持，就必须改动很多地方。 不能直接进行IO。ABC语言不能直接操作文件系统。尽管你可以通过诸如文本流的方式导入数据，但ABC无法直接读写文 件。输入输出的困难对于计算机语言来说是致命的。你能想像一个打不开车门的跑车么？ 过度革新。ABC用自然语言的方式来表达程序的意义，比如上面程序中的HOW TO 。然而对于程序员来说，他们更习惯 用function或者define来定义一个函数。同样，程序员更习惯用等号来分配变量。尽管ABC语言很特别，但学习难度 也很大。 传播困难。ABC编译器很大，必须被保存在磁带上。当时Guido在访问的时候，就必须有一个大磁带来给别人安装ABC编 译器。 这样，ABC语言就很难快速传播。

1989年，为了打发圣诞节假期，Guido开始写Python语言的编译器。Python这个名字，来自Guido所挚爱的电视剧Monty Python's Flying Circus。他希望这个新的叫做Python的语言，能符合他的理想：创造一种C和shell之间，功能全面，易学易用，可拓展的语言。Guido作为一个语言设计爱好者，已经有过设计语言的尝试。这一次，也不过是一次纯粹的hacking行为。
#### 诞生
1991年，第一个Python编译器诞生。它是用C语言实现的，并能够调用C语言的库文件。从一出生，Python已经具有了 ：类，函数，异常处理，包含表和词典在内的核心数据类型，以及模块为基础的拓展系统。 Python语法很多来自C，但又受到ABC语言的强烈影响。

来自ABC语言的一些规定直到今天还富有争议，比如强制缩进。 但这些语法规定让Python容易读。另一方面，Python聪明的选择服从一些惯例，特别是C语言的惯例，比如回归等号赋值。Guido认为，如果“常识”上确立的东西，没有必要过度纠结。 Python从一开始就特别在意可拓展性。Python可以在多个层次上拓展。从高层上，你可以直接引入. py文件。

在底层，你可以引用C语言的库。Python程序员可以快速的使用Python写. py文件作为拓展模块。但当性能是考虑的重要因素时，Python程序员可以深入底层，写C程序，编译为.so文件引入到Python中使用。Python就好像是使用钢构建房一样，先规定好大的框架。而程序员可以在此框架下相当自由的拓展或更 改。 最初的Python完全由Guido本人开发。Python得到Guido同事的欢迎。他们迅速的反馈使用意见，并参与到Python的改进。Guido和一些同事构成Python的核心团队。他们将自己大部分的业余时间用于hack Python。随后，Python拓 展到研究所之外。Python将许多机器层面上的细节隐藏，交给编译器处理，并凸显出逻辑层面的编程思考。Python程 序员可以花更多的时间用于思考程序的逻辑，而不是具体的实现细节。这一特征吸引了广大的程序员。Python开始流行。
#### 时势
我们不得不暂停我们的Python时间，转而看一看瞬息万变的计算机行业。1990年代初，个人计算机开始进入普通家庭。Intel发布了486处理器，windows发布window 3.0开始的一系列视窗系统。计算机的性能大大提高。程序员开始关注计算机的易用性，比如图形化界面。

由于计算机性能的提高，软件的世界也开始随之改变。硬件足以满足许多个人电脑的需要。硬件厂商甚至渴望高需求软 件的出现，以带动硬件的更新换代。C++和Java相继流行。C++和Java提供了面向对象的编程范式，以及丰富的对象库。在牺牲了一定的性能的代价下，C++和Java大大提高了程序的产量。语言的易用性被提到一个新的高度。我们还记得 ，ABC失败的一个重要原因是硬件的性能限制。从这方面说，Python要比ABC幸运许多。 另一个悄然发生的改变是Internet。
1990年代还是个人电脑的时代，windows和Intel挟PC以令天下，盛极一时。尽管Internet为主体的信息革命尚未到来，但许多程序员以及资深计算机用户已经在频繁使用Internet进行交流，比如 使用email和newsgroup。Internet让信息交流成本大大下降。一种新的软件开发模式开始流行：开源。程序员利用 业余时间进行软件开发，并开放源代码。
1991年，Linus在comp.os.minix新闻组上发布了Linux内核源代码，吸引大批hacker的加入。Linux和GNU相互合作，最终构成了一个充满活力的开源平台。 硬件性能不是瓶颈，Python又容易使用，所以许多人开始转向Python。Guido维护了一个maillist，Python用户就通过邮件进行交流。Python用户来自许多领域，有不同的背景，对Python也有不同的需求。Python相当的开放，又容 易拓展，所以当用户不满足于现有功能，很容易对Python进行拓展或改造。随后，这些用户将改动发给Guido，并由Gu ido决定是否将新的特征加入到Python或者标准库中。如果代码能被纳入Python自身或者标准库，这将极大的荣誉。由于Guido至高无上的决定权，他因此被称为“终身的仁慈独裁者”。
Python被称为“Battery Included”，是说它以及其标准库的功能强大。这些是整个社区的贡献。Python的开发者来自不同领域，他们将不同领域的优点带给Python。比如Python标准库中的正则表达是参考Perl，而lambda, map, filter, reduce等函数参考了Lisp。Python本身的一些功能以及大部分的标准库来自于社区。Python的社 区不断扩大，进而拥有了自己的newsgroup，网站，以及基金。从Python 2.0开始，Python也从maillist的开发方式，转为完全开源的开发方式。社区气氛已经形成，工作被整个社区分担，Python也获得了更加高速的发展。

到今天，Python的框架已经确立。Python语言以对象为核心组织代码，支持多种编程范式，采用动态类型，自动进行内存回收。Python支持解释运行，并能调用C库进行拓展。Python有强大的标准库。由于标准库的体系已经稳定，所以Python的生态系统开始拓展到第三方包。这些包，如Django、web.py、wxpython、numpy、matplotlib、PIL，将Python升级成了物种丰富的热带雨林。
#### 启示
Python崇尚优美、清晰、简单，是一个优秀并广泛使用的语言。Python在TIOBE排行榜中排行第八，它是Google的第三大开发语言，Dropbox的基础语言，豆瓣的服务器语言。Python的发展史可以作为一个代表，带给我许多启示。

在Python的开发过程中，社区起到了重要的作用。Guido自认为自己不是全能型的程序员，所以他只负责制订框架。如果问题太复杂，他会选择绕过去，也就是cut the corner。这些问题最终由社区中的其他人解决。社区中的人才是异常丰富的，就连创建网站，筹集基金这样与开发稍远的事情，也有人乐意于处理。如今的项目开发越来越复杂，越来越庞大，合作以及开放的心态成为项目最终成功的关键。 Python从其他语言中学到了很多，无论是已经进入历史的ABC，还是依然在使用的C和Perl，以及许多没有列出的其他 语言。

可以说，Python的成功代表了它所有借鉴的语言的成功。同样，Ruby借鉴了Python，它的成功也代表了Python某些方面的成功。每个语言都是混合体，都有它优秀的地方，但也有各种各样的缺陷。同时，一个语言“好与不好”的评 判，往往受制于平台、硬件、时代等等外部原因。程序员经历过许多语言之争。其实，以开放的心态来接受各个语言，说不定哪一天，程序员也可以如Guido那样，混合出自己的语言。
### Python的版本
Python在历史上主要有两个重大的版本，我们通常称之为2.7x和3x。但是由于Pyhton的历史悠久，Gui叔在1989年开始编写python的时候，早于第一版Unicode标准。晚于 Unicode 标准出现的语言都选择在支持 Unicode 编码的基础上实现自己的str类型。支持 Unicode 和来自任何语言的的文本是非常重要的。Python是一门面向世界的语言，而不只是那些支持 ASCII 码覆盖的罗马数字的语言。这就是为什 Python3在处理文本时选择“要么使用 Unicode，要么就干脆不支持”的原因。
总之现在有两个选择，学习python2，学习python3或者都学。我的建议是都学，不过以python3为主。



[Why Python3 新功能示例](https://whypy3.com)



[Python2和Python3的区别，以及为什么选Python3的原因](https://blog.csdn.net/qq_39521554/article/details/80855086)



[Python 2.7.x 与 Python 3.x 的主要差异](https://chenqx.github.io/2014/11/10/Key-differences-between-Python-2-7-x-and-Python-3-x/)

### Python的下载和安装
#### Python下载
Python最新源码，二进制文档，新闻资讯等可以在Python的官网查看到：

[Python官网](https://www.python.org/)

你可以在以下链接中下载 Python 的文档，你可以下载 HTML、PDF 和 PostScript 等格式的文档。

[Python文档下载地址](https://www.python.org/doc/)

#### Python安装
for window，官网提供三种下载文件：
* web-based installer 是需要通过联网完成安装的版本

* executable installer 是可执行文件方式安装版本
* embeddable zip file 嵌入式版本，可以集成到其它应用中

for Ubuntu，直接在终端用命令安装即可：
* Prerequsities
```
#配置安装python环境
sudo apt-get install build-essential checkinstall
sudo apt-get install libreadline-gplv2-dev libncursesw5-dev libssl-dev libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev
```
* Download Python 3.x
```
#跳转至系统用户目录的src文件夹
cd /usr/src
#从官网下载python3.x的压缩包
sudo wget https://www.python.org/ftp/python/3.x/Python-3.x.tgz
#解压压缩包
sudo tar xzf Python-3.6.8.tgz
```
* Compile Python Source
```
#跳转至python3.x解压路径
cd Python-3.x
允许第三方支持，如SSL，bz2等
sudo ./configure --enable-optimizations
#防止替换掉默认的python binary file
sudo make altinstall
```
* Check the Python Version
```
#查询当前版本
python3 -V
```
示例：若要下载最新版本3.8.0，则用8.0替换上述命令中的x即可。



相关命令为：

`apt-get install xxxx` 安装

`apt-get remove xxxx` 卸载但不删除配置

`apt-get purge xxxx` 卸载并且删除相关配置

`apt-cache search xxxx` 寻找xxxx软件，返回一系列能够下载的软件

## Python编辑器
### python编辑器的选择
一个好的代码编辑器不仅仅是一个简单的文本编辑工具，这是发生奇迹的地方，开发者编写的代码会转化为更大的项目的可用组件。鉴于这一重要性，难怪开发者会对与他们日夜共处的代码编辑器如此挑剔。每个开发者都希望拥有一个快速、易于使用且功能均衡的代码编辑器。
以下为我自己选择的python编辑器：
#### Notepad++
Notepad++编辑器我主要是代替window系统默认的文本编辑器。
这个轻量级的代码编辑器是免费开源的，速度很快且占用极少的资源，即便如此，但其功能并不马虎，开发者想要的功能几乎都有了。
[下载地址](https://notepad-plus-plus.org/download/v7.6.6.html)

#### Vim
Vim是最流行的代码编辑器之一，被称为编译器之神。
vi是“Visual interface”的简称，它在Linux上的地位就仿佛Edit程序在DOS上一样。它可以执行输出、删除、查找、替换、块操作等众多文本操作，而且用户可以根据自己的需要对其进行定制。Vi不是一个排版程序，它不象Word或WPS那样可以对字体、格式、段落等其他属性进行编排，它只是一个文本编辑程序。 vi没有菜单，只有命令，且命令繁多。它是免费开源且跨平台的，称它为代码编辑器中最为优秀经典的上古神器也不为过。尤其是在 Linux 开发者中，它享有相当高的声誉。Vim高度可定制，还可在 Dos 中运行。在刚入门开发的群体中Vim可能不会十分流行，因为它的入门学习曲线陡峭。但是一旦掌握就可以摆脱鼠标，仅凭肌肉记忆，沉静在纯净的代码世界。Vim或许在日后实际的工作中很少使用，但是它的输入逻辑是永久有效的。

[下载地址](http://www.vim.org/download.php)

#### Sublime
Sublime轻量化，跨平台，可扩展，和vim相比具有良好的图形界面环境。它支持vim模式。可是为收费软件，建议有能力的人付费使用，以支持开发者。不过不购买也可以一直使用。

[下载地址](https://www.sublimetext.com/3)

#### atom

Atom 是 Github 开源的文本编辑器，这个编辑器完全是使用Web技术构建的(基于Node-Webkit)。启动速度快，提供很多常用功能的插件和主题，可以说Atom已经足以胜任“半个IDE”了。

[下载地址](https://atom.io/)

#### Pycharm
PyCharm是一种Python IDE，其有别于以上的编辑器。
集成开发环境（IDE，Integrated Development Environment ）是用于提供程序开发环境的应用程序，一般包括代码编辑器、编译器、调试器和图形用户界面等工具。集成了代码编写功能、分析功能、编译功能、调试功能等一体化的开发软件服务套。所有具备这一特性的软件或者软件套（组）都可以叫集成开发环境。
Pycharm带有一整套可以帮助用户在使用Python语言开发时提高其效率的工具，比如调试、语法高亮、Project管理、代码跳转、智能提示、自动完成、单元测试、版本控制。主要有两个版本：professional和community。professional 表示专业版，community 是社区版，推荐安装社区版，因为是免费使用的。

[下载地址](https://www.jetbrains.com/pycharm/download/#section=windows)

[官网安装详细教程地址](https://www.jetbrains.com/help/pycharm/meet-pycharm.html)

我看了国内中文教程很鸡肋，官网英文教程很仔细足够好了，还可以在网站最上方选择系统类型，图文并茂，相信你可以看懂。