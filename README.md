# 隐藏我的应用列表
## [来源链接/项目地址]( https://github.com/Dr-TSNG/Hide-My-Applist )
[![星星]( https://img.shields.io/github/stars/Dr-TSNG/Hide-My-Applist?label=Stars )](https://github.com/Dr-TSNG)
[![发布]( https://img.shields.io/github/v/release/Dr-TSNG/Hide-My-Applist?label=Release )](https://github.com/Dr-TSNG/Hide-My-Applist/releases/latest)
[![下载]( https://img.shields.io/github/downloads/Dr-TSNG/Hide-My-Applist/total )](https://github.com/Dr-TSNG/Hide-My-Applist/releases/latest)
[![频道]( https://img.shields.io/badge/Telegram-Channel-blue.svg?logo=telegram )](https://t.me/HideMyApplist)
[![许可证]( https://img.shields.io/github/license/Dr-TSNG/Hide-My-Applist?label=License )](https://choosealicense.com/licenses/gpl-3.0/)

![横幅]( https://github.com/Dr-TSNG/Hide-My-Applist/blob/master/banner.png )

## 关于此模块
虽然检测特定的应用程序安装是不正确的，但并非每个使用 root 的应用程序都提供随机包名称支持。
这种情况下，检测到使用 root 权限的应用程序（例如虚假位置和存储隔离）就等于检测到 root 权限本身。
与此同时，一些“智能”应用会利用各种漏洞获取你的应用列表，从而为你绘制人物画像。
该模块提供了一些方法来测试您是否已经很好地隐藏了您的应用列表。
另外，它可以作为 Xposed 模块来隐藏某些应用程序或拒绝应用程序列表请求以保护您的隐私。

## 关于该模块
虽然“检测安装的应用程序是不正确的做法”，但是很愚蠢，并不是所有的插件类应用程序都提供了随机包名支持。这意味着检测到安装了根类应用程序（如假位置、存储方向）与检测到了根本身区别不大。（会认为使用检测手段的应用程序可以让你在“我就擦蹭不进去”）
同时，部分“不安分”的应用程序会利用各种漏洞绕过系统权限来获取你的应用列表，从而对你建立用户画像（比如陈叔叔将安装了V2Ray的用户分成一类），或者类似某某校园某某乐跑的软件会要求你卸载作弊软件。
该模块提供了一些检测方式用于隐藏测试您是否成功地获得了某些特定的包名，如 Magisk/Edxposed Manager；同时可作为 Xposed 模块用于应用列表或特定应用，保护隐私。