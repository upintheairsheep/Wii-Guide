---
title: "RiiConnect24"
---

{% include toc title="Table of Contents" %}

如果你需要有关本教程的任何帮助，请加入[RiiConnect24 Discord 服务器](https://discord.gg/rc24)(推荐)或[发邮件到support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

![RiiConnect24 Logo](/images/WiiRC24Logo.jpg)

[RiiConnect24](https://rc24.xyz/)允许您使用已停止服务的WiiConnect24，包括News、Forecast、Everybody Votes、Nintendo和Check Mii Out Channel以及Wii Mail。

{% capture notice-1 %}
本指南仅适用于Wii。

- 如果您想在vWii(WiiU上的Wii模式) 安装RiiConnect24，请遵循[此教程](riiconnect24-vwii)。
- 如果你想在Dolphin模拟器安装RiiConnect24，请遵循[此教程](riiconnect24-dolphin)。
{% endcapture %}

<div class="notice--warning">{{ notice-1 | markdownify }}</div>

不要在WII MINI上安装RIICONNECT24! 他不会工作，还会使它变砖。
{: .notice--danger}

#### 你需要的是

* 一张SD卡或U盘
* 一台连接互联网的Wii
* 一台电脑
* [RiiConnect24 修补程序 (Windows,、Mac 和 Linux)](https://github.com/RiiConnect24/RiiConnect24-Patcher/releases)

#### 步骤

##### 第一节 - 使用RiiConnect24修补程序

如果您无法运行RiiConnect24 修补程序，请加入 [RiiConnect24 Discord 服务器](https://discord.gg/rc24) (推荐) 或 [向support@riiconnect24.net发邮件](mailto:support@riiconnect24.net)寻求帮助。
{: .notice--info}

1. 点击上面的链接以转到修补程序所在的GitHub页面。
2. Windows下载`RiiConnect24Patcher.bat`Unix下载`RiiConnect24Patcher.sh`
3. Windows运行`RiiConnect24Patcher.bat`。 Unix打开终端并输入`bash`，然后将`RiiConnect24Patcher.sh`拖到终端并按回车。 它看起来应该像:`bash RiiConnect24Patcher.sh`。
4. 按1选择"`Start`" 然后按`ENTER`确认选择。 (注意: 这些截图来自Windows修补程序。) ![RiiConnect24 修补程序 主屏幕](/images/RC24_Patcher/1.JPG)
5. 选择您要修补的设备。 ![选择您的设备](/images/RC24_Patcher/2.JPG)
6. 在本指南中，选择"`Install RiiConnect24 on your Wii`" ![安装 RiiConnect24](/images/RC24_Patcher/3.JPG)
7. 选择"`Express (Recommended)`"。 它将为您提供所需的一切。 ![快速设置](/images/RC24_Patcher/4.JPG)
8. 选择区域。 ![选择您的区域](/images/RC24_Patcher/5.JPG)
9. 当您到这时，RiiConnect24 修补程序可以下载一些不常用的可选频道。 `[X]` 代表所选的选项。 如果您不感兴趣，按5和`ENTER`。 ![添加可选的频道](/images/RC24_Patcher/6.JPG)
10. 将SD卡或U盘连接到电脑然后选择"`1`"。 ![启用复制到SD卡](/images/RC24_Patcher/7.JPG)
11. 如果成功检测到您的设备，选择"`1`"。 如果没有，请确认SD卡或U盘上有名为`apps`的文件夹。 ![成功检测](/images/RC24_Patcher/8.JPG)
12. 请耐心等待... ![正在打补丁!](/images/RC24_Patcher/9.JPG)
13. 完成后，我们希望您花一分钟向我们发送匿名反馈。  如果不想，关闭修补程序。 所有文件都应该已经在您的SD卡上。 ![已完成!](/images/RC24_Patcher/10.JPG) ![文件已复制](/images/RC24_Patcher/11.PNG)
14. 如果它没有复制任何东西，将和`RiiConnect24Patcher.bat`同一文件夹的 `WAD` 和 `apps` 文件夹移动到SD卡或U盘。

##### 第二节 - 安装WAD

您现在将安装修补过的IOS和频道WAD，它们是RiiConnect24必须的。

1. 将SD卡或U盘插入Wii。
2. 启动Wii上的Homebrew Channel。
3. 启动Wii Mod Lite。
4. 使用Wii遥控器上的十字键，移动到`WAD Manager`， 然后移动到`wad` 文件夹。
5. 按下+突出显示文件夹里的所有wad。 当全部被选中时，按2次A安装wad。
6. 如果得到已安装更高版本频道的错误(错误 -1035)，请返回 wad 选择菜单并按 - 将其卸载，然后再次尝试安装。
7. 安装成功后，按HOME按钮返回Homebrew Channel。

##### 第三节 - 修补 nwc24msg.cfg

您现在将修补`nwc24msg.cfg`，这是使用Wii Mail必需的。

1. 启动 RiiConnect24 Mail 修补程序。
2. 修补nwc24msg.cfg只需几秒钟。 完成后，按HOME退出。

如果您无法修补nwc24msg.cfg，请加入 [RiiConnect24 Discord 服务器](https://discord.gg/rc24) (推荐) 或 [向support@riiconnect24.net发邮件](mailto:support@riiconnect24.net)寻求帮助。
{: .notice--info}

##### 第四节 - 连接

您现在需要将DNS设置为我们的服务器。 这是可选项但很推荐，因为它通过提供其它功能来增强RiiConnect24和Wiimmfi。

1. 转到 `Wii 选项`。
2. 转到`Wii 设置`。
3. 转到`第2页`，然后点击`互联网`。
4. 转到`连接设置`。
5. 选择当前连接。
6. 转到`更改设置`。
7. 转到`自动获取DNS` (不是IP地址)，然后选择`否`然后选择 `高级设置`。
8. 将`164.132.44.106`作为主要DNS。
9. 将`1.1.1.1`作为次要DNS (如果有问题，试`8.8.8.8`)。
10. 选择`确认`，然后选择`保存`。
11. 选择`OK`进行连接测试。
12. 如果连接测试成功，请选择`否`跳过Wii系统更新。
13. 转到`WiiConnect24`, 然后再次转到`WiiConnect24`，并确保它已启用。
14. 返回WiiConnect24菜单，转到`待机连接`并确保已启用。
15. 在`Slot Illumination`，我们建议您将光驱灯设置为 `Dim` or `Bright`，但这是可选的。
16. 最后，转到`互联网`，转到`User Agreements` 或 `Agreement/Contact`，点击 `Yes`。 请阅读此内容。

[Continue to Wiimmfi](wiimmfi)<br> Wiimmfi lets you play games online after the discontinuation of Nintendo Wi-Fi Connection. 你可以选择来安装。 这是可选项。
{: .notice--info}

[继续WiiLink](wiilink)<br> WiiLink允许您使用已停止服务的日本频道，如Wii no Ma 何 Digicam Print Channel。 这是可选项。
{: .notice--info}

[继续 网站导览](site-navigation) 我们有许多你可能喜欢的其他教程。
{: .notice--info}

如果得到错误107245，证明您还没有安装修补后的IOS。
{: .notice--warning}

如果您遇到错误107304或您没看到带RiiConnect24 logo的任天堂用户协议，证明您的ISP或网络正在阻止DNS。 您可以将`自动获取DNS`设置为`是`来解决。 没有它，RiiConnect24仍然工作。 或者，您可以使用我们的[DNS服务器](https://github.com/RiiConnect24/DNS-Server/releases/latest) 应用。
{: .notice--warning}

如果您得到错误 FORE000006，可能是您的Wii的时间错误。 设置正确的日期和时间，等待不超过一小时，Forecast Channel应该开始工作。
{: .notice--warning}

[如果您仍然得到FORE000006或NEWS000006错误，您需要rc24-clear-tool删除SYSCONF](https://github.com/RiiConnect24/rc24-clear-tool/releases/latest)。
{: .notice--warning}

[如果您在Forecast Channel和News Channel遇到其它错误，例如以FORE或NEWS开头的错误代码，您可以尝试使用rc24-clear-tool删除VFF。](deleting-vffs)
{: .notice--warning}

如果得到`WiiConnect24 和 Wii Shop Channel 不在您所在的国家提供服务`，前往Wii设置 -> 最后一页 -> 将国家更改为United Kingdom. 当您使用不支持的国家时，会出现出错误。 联系[support@riiconnect24.net](mailto:support@riiconnect24.net)已获得更多帮助。
{: .notice--warning}