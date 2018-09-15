notepad-ken

centos, redhat, fedora:

yum install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master


debian, ubuntu:

apt-get install ctags cscope wget unzip -y && wget https://github.com/langsim/notepad-ken/archive/master.zip -O master.zip && unzip -o master.zip && rm -rf ~/.vim && \cp -rf notepad-ken-master/.vim* ~ ; rm -rf master.zip notepad-ken-master


ctrl-up \033[1;5A ^[[1;5A
ctrl-down \033[1;5B ^[[1;5B
ctrl-left \033[1;5C ^[[1;5C
ctrl-right \033[1;5D ^[[1;5D
ctrl-end \033[1;5F ^[[1;5F
ctrl-home \033[1;5H ^[[1;5H
