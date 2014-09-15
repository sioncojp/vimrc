自分が使ってるvimrcです

[使い方]
$ rm -f .vimrc
$ mkdir -p ~/.vim/bundle
$ git clone git://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim
$ git clone https://github.com/sioncojp/vimrc.git ~/dotfile
$ ln -s /dotfile/_vimrc .vimrc
$ vim
:NeoBundleInstall

### macの場合は
$ cd ~/.vim/bundle/vimproc
$ make -f make_mac.mak
