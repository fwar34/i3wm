# i3wm
我的i3设置
fcitx要安装fcitx-gtk2 fcitx-gtk3 fcitx-qt4 fcitx-qt5这几个模块（即是fcitx-im模块）
fcitx 安装 ：
pacman -S fcitx-im fcitx-configtool fcitx-gtk3 fcitx-gtk2 fcitx-qt4 fcitx-qt5
yaourt fcitx-sogoupinyin fcitx fcitx-cloudpinyin

fonts.conf在当前用户主目录下是.fonts.conf
--------------
安装的声音管理alsamixer，菜单dmenu，终端zsh，oh-my-zsh，xfce4-terminal,tmux
----------------
xfce4-terminal设置字体为Dejavu Sans Mono Oblique，背景设置为背景图片，底纹滑动条调节透明度
-----------------
wifi链接用netctl，开机启动
------------------------------------
zsh相关配置
安装zsh oh-my-zsh zsh-completions zsh-syntax-highlighting tmux-powerline autojump powerline
-----------------------
挂载windows ntfs分区要安装ntfs-3g
---------------------------------
Linux字体文件放在/usr/share/font/，只要将字体文件拷贝到这里就可以了。
这里示例安装Windows的所有字体。
    1，新建文件夹，装Windows字体，方便管理。打开终端输入命令:mkdir win。
    2，复制Windows下 的所有字体。cd命令切换到C盘挂载的目录，进入c:\windows\Fonts。使用cp命令复制字体：cp *.ttf *.TTF /home/username/win/。这       样就把Windows的字体复制到了主目录下的win目录里面。
    3，安装字体。终端输入:mv /home/username/win/ /usr/share/font/。移动到Linux字体库中。
    4，刷新系统即刻生效，输入命令：sudo fc-cache -fv。
-----------------------------------------------
配置主题文件图标等用community/lxappearance软件
