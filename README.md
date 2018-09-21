Centos、Redhat、Fedora安装:

    yum install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

Debian、Ubuntu安装:

    apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

使用方法

    在项目的根目录打开vim，然后可通过目录树打开文件，如果语言支持，并希望使用函数跳转等功能，第一次打开项目时需要按F3更新索引。

快捷键

    F2 打开IDE模式
    F3 在C/C++、Python等语言中可以更新索引
    F4 粘贴模式
    F5 高亮光标下单词
    F6 显示隐藏字符
    F7 跳转到变量或函数定义
    F8 搜索变量或函数
    F9 保存
    F10 退出

    ctrl-r 在当前文件里搜索
    ctrl-t 在当前目录及子目录搜索
    ctrl-y 重做
    ctrl-a 全选
    ctrl-d 进入行选模式
    ctrl-f 进入选择模式
    ctrl-g 进入命令模式
    ctrl-z 撤销
    ctrl-x 剪切
    ctrl-c 复制
    ctrl-v 粘贴
    ctrl-left 跳转到左边窗口
    ctrl-right 跳转到右边窗口
    ctrl-up 跳转到上边窗口
    ctrl-down 跳转到下边窗口

部分终端需要配置的按键序列

    ctrl-up \033[1;5A ^[[1;5A
    ctrl-down \033[1;5B ^[[1;5B
    ctrl-left \033[1;5C ^[[1;5C
    ctrl-right \033[1;5D ^[[1;5D
    ctrl-home \033[1;5H ^[[1;5H    
    ctrl-end \033[1;5F ^[[1;5F

Q&A

    项目诞生缘由
        减少读写代码所需的手指运动量、大脑思维量和CPU占用率。
    开发主题
        简单即美。
        
Centos、Redhat、Fedora Install:

    yum install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

Debian、Ubuntu Install:

    apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

Operating Instruction

    Open vim in project root dir，press F2 and ctrl-left to use file tree. If language support and want to use function of jumping to variable defination，press F3 to update index when open project first time.

Function Key

    F2 open IDE mode
    F3 In C/C++、Python can update index
    F4 paste mode
    F5 highlight word under cursor
    F6 display the hidden character
    F7 jump to variable or function defination
    F8 search variable or function defination
    F9 save
    F10 quit

    ctrl-r search in current file
    ctrl-t search in current folder and child folder
    ctrl-y redo
    ctrl-a select all
    ctrl-d switch to row select mode
    ctrl-f switch to select mode
    ctrl-g switch to command mode
    ctrl-z undo
    ctrl-x cut
    ctrl-c copy
    ctrl-v paste
    ctrl-left jump to left window
    ctrl-right jump to right window
    ctrl-up jump to up window
    ctrl-down jump to down window

some teminal need to config

    ctrl-up \033[1;5A ^[[1;5A
    ctrl-down \033[1;5B ^[[1;5B
    ctrl-left \033[1;5C ^[[1;5C
    ctrl-right \033[1;5D ^[[1;5D
    ctrl-home \033[1;5H ^[[1;5H    
    ctrl-end \033[1;5F ^[[1;5F

Q&A

    Target
        Consuming less finger, less brain and less cpu to read and write code
    Theme
        Pretty is simple
