Centos、Redhat、Fedora安装:

    yum install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

Debian、Ubuntu安装:

    apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master

快捷键 

    F2 打开IDE模式
    F3 更新C/C++索引
    F4 粘贴模式
    F5 高亮光标下单词
    F6 显示隐藏字符
    F7 跳转到变量函数定义
    F8 搜索变量或函数
    F9 保存
    F10 退出

    ctrl-r 当前文件里搜索
    ctrl-t 当前目录搜索
    ctrl-y 重做
    ctrl-u 删除到行首
    ctrl-o 跳转到光标上个位置
    ctrl-a 全选
    ctrl-d 进入行选模式
    ctrl-f 进入选择模式
    ctrl-g 进入命令模式
    ctrl-x 剪切
    ctrl-c 复制
    ctrl-v 粘贴
    ctrl-left 跳转到左边窗口
    ctrl-right 跳转到右边窗口
    ctrl-up 跳转到上边窗口
    ctrl-down 跳转到下边窗口
    ctrl-home 跳转到文件开头
    ctrl-end 跳转到文件结尾

部分终端需要配置的按键序列

    ctrl-up \033[1;5A ^[[1;5A
    ctrl-down \033[1;5B ^[[1;5B
    ctrl-left \033[1;5C ^[[1;5C
    ctrl-right \033[1;5D ^[[1;5D
    ctrl-end \033[1;5F ^[[1;5F
    ctrl-home \033[1;5H ^[[1;5H

Q&A
    项目诞生缘由
        减少读写代码所需的手指运动量、大脑思维量和CPU占用率。
    开发主题
        简单即美。
    这东西是啥?
        将vim配置成一个好用的代码编辑器的vim脚本.读写C/C++/Python/Golang代码已测好用。
    兼容性怎么样?
        不怎么样,运行安装命令后部分终端就可以直接用了,部分终端还需要配置下按键序列才可用,有没有一些终端根本没法使用我不清楚。
    比原生vim好在哪里?
        最大的好处,不用再按ESC了,比我以前用到的VIM功能一点没少.
    本身就是一个vim脚本,为什么项目名没有vim字样?
        因为vim以快捷键的闻名,而这个项目里找不到vim快捷键的影子.

