# 「阅读」APP 精品书源

[![GitHub license](https://img.shields.io/badge/license-GPL--3.0-orange?style=flat-square&color=0f6adb)](https://github.com/XIU2/yuedu/blob/master/LICENSE)
[![GitHub Star](https://img.shields.io/github/stars/XIU2/yuedu.svg?style=flat-square&label=Star&color=0f6adb)](https://github.com/XIU2/yuedu/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/XIU2/yuedu.svg?style=flat-square&label=Fork&color=0f6adb)](https://github.com/XIU2/yuedu/network/members)
[![YUEDU.XIU2.XYZ](https://img.shields.io/static/v1?label=%20&message=YUEDU.XIU2.XYZ&style=flat-square&labelColor=1172EB&color=0f6adb&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAA1ElEQVR42mMULHr9n4ECwEhVA971ijDUb/7CMPnAD4Y4M3aGCeG8ODUKFb/BNCDYgI1hdiwfXBIbQFcDNwBkO0wQXRGyHDofqwHOaiwMq9MFGDwnvWfw0WNnyHbgYnCf+J7h9KO/xBkAYuPzN1EGoIcDLnnaGUCRF5D5INqk/R3DvTf/iI8FmAtgBtRt+sJw8ckfho1ZAnAxnAYgawYBH21WhkVJ/HAxgglJlJuR4cnHfwzsLIwo/o8yYWOYEsnH8PHbP4bStV8Y1lz4hZmUyQEUGwAAWJ624X5VLdcAAAAASUVORK5CYII=)](https://yuedu.xiu2.xyz)

本项目每天抓取「阅读」官方微信公众号中分享的优质精品书源，制作成一个单独的书源文件，方便大家一键导入！  
彻底解决了「阅读」官方公众号每次更新都需要打开微信手动复制导入的痛点了！现在只需要定期重复导入该书源（二维码或URL）即可，省时省力！  
> 为了避免阅读作者打爆我的狗头，所以... **「阅读」官方微信公众号：「开源阅读软件」**  

****

## 更新日志：
- **更新：** 网站域名及服务器（解决部分地区无法访问或速度慢的问题）。
- **新增：** 阅读3.0书源。
- **新增：** 校验书源功能。  
—— 脚本会把无法访问的书源网站去除。  
—— 该功能对于那些书源规则失效（而不是书源网站挂了）的书源是无效的，所以依然可能存在小部分失效书源。
- **修复：** 昨天脚本新抓取的书源有问题，已经修复了格式不对的问题（以后每次更新前会先检查JSON格式是否正确再更新）。
- **新增：** 历史书源文件：https://yuedu.xiu2.xyz/old
- **新增：** 网站将显示书源更新时间及数量。

****

## 软件介绍：
「阅读」我就不多介绍了，我见过不少人安利，我直接贴酷安的介绍吧。  
https://www.coolapk.com/apk/256030

****

## 下载地址：
- **软件下载地址：** https://www.coolapk.com/apk/256030
- **软件开源地址：** https://github.com/gedoor/legado
- **官方下载地址：** https://github.com/gedoor/legado/releases

****

## 书源地址：
书源每日更新，大家可以定期导入一次~ 放心！导入时会自动去重复的！
- **书源分享地址：** https://yuedu.xiu2.xyz
- **网络导入地址：** https://yuedu.xiu2.xyz/shuyuan

- **本地导入地址：** 去上面的书源分享地址里点击 **\[下载文件\]**
- **历史书源文件：** https://yuedu.xiu2.xyz/old

****

## 导入步骤：
### 二维码导入(推荐)：
打开「阅读」APP点击右下角的 **\[我的\] 按钮 - \[书源管理\]**(最下方第一张图)，这时候再点击右上角的 **\[三圆点\] 按钮 - \[二维码导入\]**(最下方第二张图) - 然后手机扫描下方二维码即可即可。  

![](https://yuedu.xiu2.xyz/dist/img/img-02.png)

****

### 网络导入(推荐)：
打开「阅读」APP点击右下角的 **\[我的\] 按钮 - \[书源管理\]**(最下方第一张图)，这时候再点击右上角的 **\[三圆点\] 按钮 - \[网络导入\]**(最下方第二张图) - 输入下面的网络导入地址并点击 **\[确定\]** 按钮即可（最下方第三张图）。  
- **网络导入地址：** https://yuedu.xiu2.xyz/shuyuan

****

### 本地导入：
打开 [书源分享地址](https://yuedu.xiu2.xyz) 后点击 **\[下载文件\]** 即可下载 **shuyuan.json** 文件，存放到手机中任何你能找到的位置。  

打开「阅读」APP点击右下角的 **\[我的\] 按钮 - \[书源管理\]**(最下方第一张图)， 这时候再点击右上角的 **\[三圆点\] 按钮 - \[本地导入\]**(最下方第二张图) - 选择 **shuyuan.json** 文件导入即可（最下方第四张图）。  

![](https://yuedu.xiu2.xyz/dist/img/img-04.png)

****

### 历史书源导入：

先去[这里](https://yuedu.xiu2.xyz/old)找到你要导入历史书源，例如：**shuyuan_20191014.json**  

那么网络导入地址为：https://yuedu.xiu2.xyz/old/shuyuan_20191014.json  

自行替换 URL 最后的文件名即可。

> 如果需要下载到本地，那么可以浏览器打开网络导入地址，然后 **右键 - 另存为...**

****

## 如何听书？

> 鉴于一些人有这方面需求，我就特意说明一下。  

「阅读」APP 支持朗读文字，但是依靠的是手机的 TTS（文字转语音引擎），很多手机自带的并不支持朗读中文（小米的好像可以），所以需要安装额外的TTS，我推荐两个：
- **Google 文字转语音引擎**  
- **讯飞语记**  

谷歌的只有女音，讯飞的有好几个音色，我感觉讯飞念中文更好点（谷歌念英文更好点）。

> 讯飞语记安装后需要去 **通用设置 - 语音合成设置 - 开启\[合成系统接口\]** ，然后根据需求去上面的系统默认发音人处设置发音人（音色）就行了。  

****

## 许可证
The GPL-3.0 License.  
