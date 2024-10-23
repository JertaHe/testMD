实验一课程参考资料：
- **实验一指导书.pdf**
- **华为云环境搭建.pdf**
- **系统环境搭建与基本操作的熟悉-实验指导书**
# 环境搭建
华为云ECS搭建、个人电脑VMware装载openEuler 22.03LTS，遵循实验指导书即可成功完成。

同时熟悉以下指令：
	uname -a                                查看总体架构
	cat /etc/os-release                  查看操作系统信息
	lscpu                                       查看CPU信息
	free                                          查看内存信息
	fdisk -l                                     查看磁盘信息
	top                                          查看资源实时信息
	ip addr                                    查看IP地址

华为云启动流程：
1.终端连接华为云:
	在个人电脑启动 powershell/cmd 命令行窗口，输入:
	<center></center>
	ssh root@
	即可成功连接我的华为云。输入密码即可登录。
2.WinSCP连接华为云:
	图形化界面，易操作。

华为云实验流程：
1. 有相应的.c代码文件.
2. 用WinSCP存放到 /usr/local/src/test 文件夹中.
3. 在PC机powershell通过ssh访问到 /usr/local/src/test 文件夹.
4. 键入命令gcc -o [name] name.c [others] 进行编译.
5. 键入命令 ./name 就可以运行，在终端查看结果.

VMware虚拟机掌握内容:
	指令：
		cd /usr/src/kernels             进入核相关内容文件夹
		netstat -tulnp | grep 21      根据关键字21查看相关网络连接
		systemctl stop vsftpd         停止vsftpd服务
		systemctl restart vsftpd     重启vsftpd服务
		systemctl start vsftpd        开启vsftpd服务
	实验流程：
		1. 在虚拟机中输入:
		    ftp localhost
			以开启ftp服务.
			用户名anonymous 密码为空.
		2. 在PC机文件管理器中输入:
			<center></center>
			ftp://192.168.157.130
			即可访问虚拟机上的文件.
			文件夹位置为 var/ftp/pub/
# 实验一 Task1





# 实验一 Task2






# 实验一 Task3
