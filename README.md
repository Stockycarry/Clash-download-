# Clash-for-PC
# 下载链接:https://github.com/Fndroid/clash_for_windows_pkg/releases/download/0.20.24/Clash.for.Windows-0.20.24-win.7z
# 1、安装与使用
	
	1、通过链接下载后安装，无脑下一步即可，打开桌面的 Clash for Windows.exe（部分电脑上没有显示后缀，即文件名叫 Clash for Windows）
	 ![image](https://github.com/Stockycarry/Clash-download-/blob/main/clash-win-01.webp)

	2、通过订阅链接下载配置文件，在(Profiles)配置文件一栏里面，复制你购买订阅的链接 URL，然后点击 download（下载）按钮下载订阅文件
	![image](https://github.com/Stockycarry/Clash-download-/assets/82073648/e3b491d7-793d-4aad-a61f-44002536cdbf)

	3、切换到 proxies（代理）一栏，会看到很多节点，单击无线图标可以查看延迟等。选择你的节点，用鼠标点下即可。其他不懂的不要动。
	![image](https://github.com/Stockycarry/Clash-download-/assets/82073648/c7736b30-e048-4686-9867-3956653114a7)

	4、点击常规,打开系统代理和开机启动两项即可。如果需要局域网共享可以打开允许局域网连接，默认是关闭。
	![image](https://github.com/Stockycarry/Clash-download-/assets/82073648/b73f7065-1f11-471c-997f-74598a541861)

	这样，打开浏览器即可访问代理所属环境的网站了。
	
# 2、windows的汉化
链接：https://github.com/BoyceLig/Clash_Chinese_Patch/releases/download/0.20.24/app.zip
下载 app.7z 或 app.zip 文件(两个压缩包内容一样)后，解压压缩包，请自行替换下列路径中的 app.asar 文件（app.asar文件本身是个压缩包，不需要解压，直接替换）
# 路径：Clash for Windows\resources\app.asar

# 3、代理模式（小白可以不看） 

	全局（Global）：所有请求直接发往代理服务器

	规则（Rule）：所有请求根据配置文件规则进行分流

	直连（ Direct ）：所有请求直接发往目的地
	
# 4、上不了网
	方法一：删除先前的配置文件，然后通过 url 重新下载就可以解决问题了。
	
	方法二：在任务栏的搜索框中输入“cmd”，右键点击命令提示符，选择以管理员身份运行，在管理员：命令提示符窗口中执行以下的命令：netsh winsock reset 回车。然后重启电脑，再开 clash，Ok
	
	方法三：打开系统设置—-网络和 Internet 设置—-关闭代理，退出 clash,在重启 clash 即可（如下图）。
	![image](https://github.com/Stockycarry/Clash-download-/assets/82073648/f43968c8-b0bf-44c9-910f-dd963ed9adc4)

 

# Clash-for-Android
# 下载链接：https://github.com/Stockycarry/APK-for-android/releases/download/application/clash-for-android.apk
下载release 中的apk安装使用即可，将购买的订阅链接URL 添加然后下载配置文件即可。
