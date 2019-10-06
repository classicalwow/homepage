# 手机玩魔兽世界

## quick start


### 英伟达串流

原理很简单，可以简单理解成远程桌面玩游戏，重点是就是英伟达从显卡级别将渲染数据通过网络发送到客户端上，延迟低，对网络的要求高，占用带宽大且要求延迟低

户外4g没啥压力，不过费流量 1080P 60fps 需要20mbps 720p 60fps 需要10mbps 

[具体教程](https://www.iplaysoft.com/moonlight-stream.html)


### 手机按键映射

将手机客户端的手柄按键映射到PC上，需要安装一个[wowmapper客户端](https://github.com/topher-au/WoWmapper/releases/tag/8.2.0)，他会自动映射，同时需要安装[consoleport插件](https://www.curseforge.com/wow/addons/console-port/files/2797039)，专门针对手柄在魔兽的体验优化,这里有[手柄体验视频](https://v.youku.com/v_show/id_XMTY2NTA4NzEyNA==.html?spm=a2h0k.11417342.soresults.dtitle)

### 外网穿透

接下来需要解决在户外玩游戏，需要外网穿透

1.如果你家宽带是独立公网Ip的话 推荐使用路由器自带端口映射或者RMZ，moonlight端口占用如下：

![moonlight](../img/moonlight_port.png)

2.如果你家宽带不是独立的话,请自行google 内网穿透，我家是独立Ip，哈哈

最后你需要花生壳绑定域名，避免Ip更变导致无法正常游戏


### 远程桌面

远程桌面是为了方便用手机开启各种软件，比如加速器，xpadder等软件

推荐使用 teamviewer 或者 vncserver，不要用软件自带的远程桌面，因为他会注销当前用户


### 显卡欺骗器

由于windows的限制，显卡必须连接显示器，为了可以关闭显示器，你需要一个显卡欺骗器，是一个虚拟的usb显示器，可以切换显示器，切换到显卡欺骗器就可以关闭显示器了，[淘宝地址](https://detail.tmall.com/item.htm?id=564633453403&spm=a1z09.2.0.0.47872e8d5G9qO2&_u=d3td1r1a69a)


### 远程开机

为了节约用电，最好当需要玩的时候远程开机。

*  主板支持

设置bios开启远程唤醒，然后用Linux的路由器安装唤醒插件给主板发送指令唤醒，[具体教程](https://www.znds.com/tv-948915-1-1.html)

*  主板不支持

如果主板不支持，可以购买一个[开机卡](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.47872e8d5G9qO2&id=560152732327&_u=d3td1r1494f)插入主板，自带唤醒软件




## 使用总结

1. 通过路由器远程开机

2. 用过teamviewer 或者 vnc 开启远程桌面开启加速器和xpadder

3. 打开moonlight开启wow

4. 通过moonlight或者远程桌面关机



  


