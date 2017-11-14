# win7-vmware-centos6.4
本视频教程介绍在win7旗舰版 64位下安装虚拟机及centos6.4的详细操作过程,包括视频教程,软件下载,注意事项,安装咨询qq.
win7下安装vmware+centos6.4
--by coding60.com qq: 761593965
一，软件安装环境：
  Operating System: Windows 7 旗舰版 64-bit (6.1, Build 7601) Service Pack 1 (7601.win7sp1_ldr.170913-0600)
  Language: Chinese (Simplified) (Regional Setting: Chinese (Simplified))
System Manufacturer: Hewlett-Packard
 System Model: HP 431 Notebook PC              
 BIOS: InsydeH2O Version 03.60.50F.22
 Processor: Intel(R) Core(TM) i3-2330M CPU @ 2.20GHz (4 CPUs), ~2.2GHz
 Memory: 4096MB RAM
二、软件版本
1. VMware-workstation-full-11.1.0-2496824
2. CentOS-6.4-i386-bin-DVD1
三、软件下载
1. VMware：
2. CentOS：
3.如不能下载请联系QQ ：761593965

四、注意事项：
虚拟机vmware 11 ,出现错误“此主机支持 Intel VT-x，但 Intel VT-x 处于禁用状态”的问题，
 Intel VT-x 即Virtualization Technology, 虚拟化技术，英特尔处理器内更出色的虚拟化支持Intel VT-x 有助于提高基于软件的虚拟化解决方案的灵活性与稳定性。换句话说是在单CPU上支持多系统的技术。

如何解决
1.	重启系统，进入BIOS，我的系统是系统启动前按ESC,再按F10键进入BIOS的
2.	选择advanced选项卡，选择CPU setup,按enter键进入
3.	选择Intel Virtualization Technology，选择，按enter
4.	选择Enable，按enter键。 
5.	保存退出，重启 
6.	再次进入vmware,就可以正常安装了。




视频教程及软件下载地址：

60编程网

http://d.coding60.com
 

