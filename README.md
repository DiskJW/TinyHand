![GIF](/_img/TinyHand.gif)

这是对2018年12月9日发布的“[thinkingcursor](https://github.com/MY1L/thinkingcursor)”光标的更新，但改成更好记的名称：**TinyHand**

主要是让动画更流畅及修正像素级的错误。

如先前所说扩大为系列，如今更支持**黑暗模式**和中指，政确力UpUp!

## 一览
![Screenshot](/_img/Screenshot.png)

一共3大系列（肤色）：ZRKL、KOFJI、ANNYUI（名称越长颜色越暗）和各种小分支。

给ZRKL做的手势比较多。

## 下载
全部打包：[Releases · MY1L/TinyHand](https://github.com/MY1L/TinyHand/releases)

## 安装

### 勤快向
先把光标们放到一个你确定不会动的位置，控制面板→鼠标→指针，创建一个新光标方案逐个改动。优点是不会有文件倒进系统盘。
### 懒人向
对`.inf`右键点“安装”，这会把一堆光标一股脑儿全倒进`%SYSTEMROOT%\Cursors\TinyHand`系统光标文件夹里，并在注册表`HKCU\Control Panel\Cursors\Schemes`生成一个光标方案。等复制完（很快的）后打开 控制面板→鼠标→指针选`TinyHand ***`方案，点应用。

考虑到ZRKL有些光标与KOFJI重复，决定以KOFJI为基准。装ZRKL需要先安装`KOFJI***.inf`，当然手动安装无所谓。

## 卸载
控制面板→鼠标→指针，删除方案，再删除对应光标。如果是用`.inf`安装的，还要进系统光标文件夹删`TinyHand`文件夹。