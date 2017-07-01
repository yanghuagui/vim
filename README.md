# vim
personal useful vim config files
说明：所有插件均只在Debian-based distros上验证过，其他发行版和Windows没有验证过
    Debian 8 jessie & Ubuntu 14.04.5 LTS
使用该插件配置前请确保由执行过以下操作
1. sudo apt-get install git vim ctags cscope vim-youcompleteme
2. 针对vim-youcompleteme需要再执行vim-addons install youcompleteme
3. cd ~ && git clone https://github.com/yanghuagui/vimconfig
4. cd ~/vimconfig && git submodule init && git submodule update
5. cp ~/vimconfig/.vim/* ~/.vim/ && cp ~/vimconfig/.vimrc ~/ #这里注意路径，一开始vim-addons install youcompleteme后有些目录已经存在
6. 进入vim命令模式：PluginInstall 并等待安装完成
