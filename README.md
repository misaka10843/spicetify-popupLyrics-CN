# spicetify-popupLyrics-CN
更适合中国用户的spicetify悬浮歌词插件popupLyrics

## 前言

此优化插件添加了中文翻译，并且添加`NeteaseCN`选项

（`NeteaseCN`选项为**在有中文翻译时使用网易云音乐翻译，没有时使用spotify官方歌词**）

![image.png](https://s2.loli.net/2022/09/16/xtNcMU2SjgmwZrT.png)

## 食用方法

(PS：如果您没有安装spicetify，请看下面的[spicetify安装](https://github.com/misaka10843/spicetify-popupLyrics-CN#spicetify%E5%AE%89%E8%A3%85))

1.下载**本仓库**的`popupLyrics.js`并放在`%USERPROFILE%\AppData\Roaming\spicetify\Extensions`中(如有请替换，并且直接跳到第三步)

2.打开`%USERPROFILE%\AppData\Roaming\spicetify\config-xpui.ini`并找到`extensions`那一行，在行尾添加`|popupLyrics.js`(**或者**在等于号空格`=<空格>`后面添加`popupLyrics.js|`)

3.打开**CMD**或者**终端**输入`spicetify apply`后输入`y`即可应用

4.右键上方UI的麦克风icon即可设置悬浮歌词

## spicetify安装

因为在中国大陆，GitHub已经被屏蔽，所以请在运行下部分命令时打开全局加速器来提升速度

使用**终端**/**Powershell**运行以下命令即可

```
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-cli/master/install.ps1 | iex
iwr -useb https://raw.githubusercontent.com/spicetify/spicetify-marketplace/main/resources/install.ps1 | iex
```
