### 通用教程
1.先在机器人注册账号并拿到服务器地址


![](https://i.postimg.cc/ydNvjm5j/image.png)


---

2.在设备安装好Emby软件

---

3.输入服务器地址和账户密码并登录


![](https://i.postimg.cc/pXVzFWwQ/image.png)


界面都大同小异，这个不多说

---

### 注意事项
本文所有下载地址，都加入了下载反代加速服务，如果你有相关 “科技” ，反而会变得缓慢，请自行复制链接地址，去掉最前方的加速地址。

---

### Windows客户端
下载地址：

[Windows版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Windows_3.0.20_v2.0.Carnival.exe)

在下载站Emby目录里的Windows文件夹，下载后管理员身份运行，打开软件，`选择添加服务器` 输入机器人所发的主机名和端口号，输入自己账号密码，登录即可。

---

### MacOS客户端
下载地址：

[商店版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.MacOS_2.1.6_v2.Carnival.zip)

[Electron版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.MacOS_3.0.15_v9.0.Carnival.Electron.zip)

MacOS有两个版本，分为商店版和Electron版，界面没差别，至于播放能力和别的，可以自行体验哪个更适合你自己。

- 安装需要去掉APP隔离属性：sudo xattr -r -d com.apple.quarantine `APP路径`
- 如果卸载后需要清除残留文件，商店版:`rm -rf library/Containers/com.emby.mobile`，Electron版:`rm -rf library/Application*Support/Emby*Theater`。

---

### Linux客户端
下载地址：

[Linux版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Linux_3.0.20_v2.0.Carnival.deb)

客户端适用：Debian x64 / Ubuntu x64

这个用的人很少，真正日常拿来用的，也不需要我教了（笑）

卸载：`sudo apt-get purge emby-theater ; sudo apt-get autoremove ; sudo apt-get autoclean ; dpkg -l |grep ^rc|awk ‘{print $2}’ |sudo xargs dpkg -P emby-theater ; sudo apt-get update`

---

### 电视端

下载地址：

[普通版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Android.TV_2.0.83g.common.apk)

[异类版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Android.TV_2.0.83g.heterogeneous.apk)

[斐讯版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Android.TV_2.0.83g.PHICOMM.apk)

这里提供的电视端有三个版本，普通版，异类版，和斐讯版

- 普通版可以装在大部分的电视和电视盒子，谷歌TV棒等等都可以
- 如果使用普通版，打不开，字幕显示问题，等等各类疑难杂症，可以尝试异类版
- 斐讯版适用斐讯N1，和各类低版本安卓的电视和电视盒，自己查看各自的系统版本，如果是安卓5的话都用这个版本

---

### Android版

下载地址：

[普通版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Android_3.2.32_v17.32.Carnival.apk)

[MIUI设备专版](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/Emby.for.Android_3.2.32_v17.32.Carnival._MIUI.apk)

[MXPlayer](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V99.client/MX.Player.for.Emby_1.42.13_v5.64.apk)

安卓这里也提供了两个版本，普通版和MIUI。

大多数设备直接用普通版即可，MIUI设备请使用MIUI专版。

---

### IOS版

Infuse开心版客户端（自己想办法怎么用）： [下载地址](https://ghproxy.com/https://github.com/EmbyTV/emby/releases/download/V7.5.8-infuse/Infuse7.5.8.ipa)

IOS可以使用的有三个版本：

- 应用商店官方版（需要支付一定的doller来购买播放权限，不买用不了，富哥可以购买一下来支持下官方）
- Fileball（需要等待开发者上架）
- Infuse（IOS平台拥有最强解码能力的播放器，对HDR，DTS等支持是最好的，富哥可以买，但是也可以用Fileball来拉起播放）

三个客户端各自使用方法也是大同小异，就不细说了。