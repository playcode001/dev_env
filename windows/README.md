###Vim安装与设置

系统环境为Win7 64bit + Vim7.3 64bit。假设安装目录为D:\Vim。
http://code.google.com/p/vim-win3264/
首先下载vim73-x64.zip解压到D:\Vim。运行cmd
###

###安装Git

Vundle在Linux非常容易安装，在Windows下首先需要安装Git。
下载msysgit并安装。同时建议安装一个TortoiseGit作为图形界面。

下载地址如下：
https://code.google.com/p/msysgit/downloads/list

https://code.google.com/p/tortoisegit/wiki/Download?tm=2

### 遇到的问题

1.ctag安装问题
Taglist: Exuberant ctags (http://ctags.sf.net) not found in PATH.  Plugin is not loaded.

解决方法：
Windows:
let Tlist_Ctags_Cmd = 'd:\tools\ctags.exe'

Unix:
let Tlist_Ctags_Cmd = '/usr/local/bin/ctags'

