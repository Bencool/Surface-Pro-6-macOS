<h1>Surface Pro 6 黑苹果  CLOVER 配置文件</h1></br>
Surface Pro 6 的UEFI BIOS和别的机型BIOS相比较处在一个很特殊的地位，我光是为了解决卡++++++++就花了将近一个月，总过花了一个月17天终于解决了UHD620内屏黑屏的问题！这背后总共试验了1200多次试错，我也收获了对surface pro系列的一些特性了解，整个过程我很享受</br>
<h2>配置信息</h2>
<ul>
  <li>品牌型号：Microsoft surface pro 6</li>
  <li>CPU： Core i5-8250U</li>
  <li>显卡：UHD Graphics 620 128MB</li>
  <li>内存：8GB</li>
  <li>声卡：ALC298</li>
  <li>无线网卡：Marvell Marvell AVASTAR Wireless-AC Network Controller</li>
  <li>显示屏：LGD0555 12.3 英寸</li>
  <li>显示屏比例：3:2</li>
  <li>分辨率： 2736 x 1824</li>
  <li>硬盘：	SK HYNIX Skhynix BC501 NVMe 128GB</li>
</ul>
<h2>macOS 版本：</h2>

<ul><li>macOS 10.13.6 - macOS 10.14.x，我目前使用macOS 10.14.2正式版</li></ul>
<h2>CLOVER版本：</h2>
<ul><li>CLOVER 4877。</li></ul>
<h2>SMC版本：</h2>
<ul><li>使用VirtualSMC 1.2.7</li></ul>
<h2>目前完成：</h2>
<ul>
  <li>内屏显示内建正常；</li>
  <li>亮度调节正常；</li>
  <li>外接HDMI正常，可以同时使用内屏；</li>
  <li>ALC298内建正常；</li>
  <li>休眠睡眠唤醒正常；</li>
  <li>使用原装网线转接卡正常使用en0，同时可以使用外置USB网卡en1；</li>
  <li>iCloud登陆正常；</li>
  <li>App Store登陆正常，下载正常；</li>
  <li>iMessage登陆正常</li>
  </ul>
TPS：我没有使用代码仿冒一个无用的en0，我是先装好系统后，首先使用Apple 有线转接网卡进行联网，此时系统自动内建en0，然后再安装外置USB网卡驱动即为en1。
<h2>未进行项目：</h2>
<ul>
<li>音量+-按键；</li>
<li>触控板；</li>
<li>摄像头；</li>
<li>内置SD卡槽；</li>
<li>全球暂时无解：触摸屏、内置蓝牙、内置WiFi；</li>
<li>期待你的完善分享！</li>
</ul>
<h2>安装过程：</h2>
使用config-Install.Plist 文件进行全程安装，安装完成后先用这个配置文件进系统使用kexts Uiltiy 进行重建缓存，然后重启使用默认配置文件即可驱动内屏！</br>
特别提示：</br>
如果重建缓存之后重启跑玩-v代码后重启的，那么选择congfig-out-Dispaly.Plist 这个配置文件，然后连接上显示器就可以正常进入驱动后的系统，然后再一次重建缓存，重启之后使用默认配置文件就可以驱动内屏了！</br>
<h2>系统截图</h2>
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/1.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/2.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/3.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/4.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/5.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/6.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/7.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/8.jpg" />
<img src="https://github.com/molie34/Surface-Pro-6/blob/master/images/9.jpg" />

