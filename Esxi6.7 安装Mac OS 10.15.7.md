## 一、准备工作
 * Esix6.7
 * MacOS Catalina 10.15.7
 * 免驱显卡 GTX740
 * 解锁文件  [esxi-unlocker-master.tar](https://cousin.lanzoui.com/ieJNesak42j "支持6.7-7.0 密码：xa")
 ## 二、解锁虚拟机
 1. 先把解锁文件和Catalina 上传到esxi存储里面。
 <br><img src="https://pic.imgdb.cn/item/610cf0445132923bf8fa3a7f.png" >  
 2. 打开esxi ssh的服务
 <br>
 <img src="https://pic.imgdb.cn/item/610cf0445132923bf8fa3a79.png" >
 3. 终端连接，进入到磁盘存储目录对解锁脚本进行解压运行并运行
 <br>解压命令<font color=red size=4.5>tar –xZvf esxi-unlocker-master.tar.gz</font><br>
 运行脚本并重启<font color=red size=4.5>./esxi-install.sh && reboot</font>
 <br><img src="https://pic.imgdb.cn/item/610cf49d5132923bf80713a5.png"><br>

## 三、安装
创建虚拟机,配置如图，可以根据自己的配置自定义，直通显卡记得安装完成之后添加，创建安装的时候不要安装不然无法安装
<img src="https://pic.imgdb.cn/item/610cf7025132923bf80e2901.png">
<img src="https://pic.imgdb.cn/item/610cf7025132923bf80e2918.png">

附上安装完成远程图(我这边已经映射到外网了，Mac vnc端口是5900)<img src="https://pic.imgdb.cn/item/610cf86a5132923bf8120710.png">
