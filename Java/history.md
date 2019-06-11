# Java发展历史
了解java发展的历史对理解各种java技术和对应解决的问题有巨大的帮助。
## Java的起源
20世纪90年底（198几年），硬件领域出现了单片式计算机系统，这种价格低廉的系统一出现就立即引起了自动控制领域人员的注意，因为使用它可以大幅度提升消费类电子产品（如电视机顶盒、面包烤箱、移动电话等）的智能化程度。

为了抢占市场Sun公司在1991年成立了一个称为Green的项目小组，其目的是开拓消费类电子产品市场，例如，交互式电视、烤面包箱等。

Sun内部人员把这个项目称为“Stealth计划”后来改名为“Green”。

由于C++的优势，考虑采用C++编写程序。但对于硬件资源极其匮乏的单片式系统来说，C++程序过于复杂和庞大，另外由于消费电子产品所采用的嵌入式处理器芯片的种类繁杂，如何让编写的程序跨平台运行也是个难题。

最后，他们想要一种易于移植到各种设备上的平台。

在当时，比尔·乔伊提议SUN公司的工程师应该在C的基础上，开发一种面向对象的环境。

最初，高斯林试图修改和扩展C的功能，他自己称这种新语言为C–，但是后来他放弃了。他将要创造出一种全新的语言，被他命名为“Oak”（橡树），以他的办公室外的树而命名。

至于这Oak怎么变成了Java?

因为商标搜索结果显示，Oak已被一家显卡制造商注册，因此团队找到了一个新名字即Java。

##JDK1.0
1991年，Sun公司成立Green项目。Oak语言诞生。

1992年11月，Sun公司为Green项目成立FirstPerson公司。同年，因为想要做高端互动的电视机顶盒的投标失败，在电视厂商并没有任何收益，所以被并回SUN公司。

1992年12月3日，被命名为Star7的面向一种类PDA的这台设备进行了展示，这种设备有鲜艳的图形界面和被称为“Duke”的智能代理来帮助用户。

第一个成果是可触摸控制的手持家庭娱乐设备控制器，名为Star7（starseven）。

1993年，FirstPerson公司重定位Oak。转向到网络应用领域（背景：WWW开始席卷全球）。

1994年6月，Oak技术包括源代码全部免费公开。Oak开发出小型万维网浏览器WebRunner，后更名为HotJava。Oak编写的Applet让网页由静态转成动态。

1995年，Oak注册登记时，发现该名已被占用，遂更名为Java。

1995年5月23日，Sun公司在Sun world会议上正式发布Java和HotJava浏览器。

1996年1月23日，Sun公司发布了Java的第一个开发工具包（JDK 1.0），这是Java发展历程中的重要里程碑，标志着Java成为一种独立的开发工具。这时jdk中包含的类和接口一共211个。

##JDK1.1
1997年2月19日发布，类和接口数量：477
新的jdk改进了AWT事件模型，新增了JavaBean、JDBC技术，并支持内部类、RMI、反射技术。
##JDK1.2
1998年12月8日发布，类和接口：1524
新功能和特效：集合框架、JIT编译器、JFC、JDBC可滚动结果集、BLOB、CLOB、批处理
##JDK1.3
2000年5月8日发布，类和接口：1840
新功能和特效：内置HotSpot JVM、改进RMI对CORBA的兼容性、动态代理相关类、Sound API、JNDI、JPDA（Java平台调试器体系
##JDK1.4
2002年2月26日发布，类和接口的数量：2723
新功能和特效：计算能力提升、XML处理、Logging API、JDBC 3.0 API、断言、支持正则表达式、NIO、支持IPv6、图形I/O API、Java Web Start、Preference API
##JDK1.5
2004年4月发布，
新功能和特性：泛型、枚举类型、自动装箱拆箱、可变参数varargs、注解、静态导入、新的线程模型和并发库Thread Framework。
##JDK1.6
2006年12月11日发布，类和接口的数量：3793
新功能和特性：引入了一个支持脚本引擎的新框架、UI的增强、对WebService支持的增强（JAX-WS2.0和JAXB2.0）、一系列新的安全相关的增强、JDBC4.0、Compiler API、通用的Annotations支持
##JDK1.7
2011年7月28日发布，类和接口的数量：4042
新功能和特性：钻石语法（泛型推断）、异常的改进、JVM多语言支持、TWR（try-with-resources）、NIO.2。

1. 数值可加下划线用作分隔符（编译时自动被忽略）如：int binary= 100_1;
2. 支持二进制数字，如：int binary= 0b1001_1001;
3. switch的增强（switch中可以使用字串了）
4. 钻石语法（泛型推断）

##JDK1.8
2014年3月19日发布，
新功能和特性：Lambda表达式、接口的默认方法与静态方法、方法引用、重复注解、扩展注解的支持、Optional、Stream、Date/Time API (JSR 310)、JavaScript引擎Nashorn、Base64。
[参考资料](https://www.cnblogs.com/pkufork/p/java_8.html)
##JDK1.9
2017年9月21日发布
新功能和特性：模块化——Jigsaw、交互式命令行——JShell、默认的垃圾回收器——G1、进程操作改进、竞争锁的性能优化、分段代码缓存、优化字符串占用空间 
[参考资料](http://geek.csdn.net/news/detail/196632)

