自分が使ってるvimrcです  
  
[使い方]  
$ rm -f .vimrc  
$ mkdir -p ~/.vim/bundle  
$ git clone git://github.com/Shougo/neobundle.vim ~/.vim/bundle/neobundle.vim  
$ git clone https://github.com/sioncojp/vimrc.git ~/dotfile  
$ ln -s ~/dotfile/_vimrc .vimrc  

##### unite.vim does not work this version of Vim "702"対策
https://github.com/Shougo/unite.vim/releases/tag/ver.6.1に戻す
$ git checkout cec560e4b2cc8f0dab14a3d18dca1885b333b6b3
$ vim  
:NeoBundleInstall  
  
### macの場合は  
$ cd ~/.vim/bundle/vimproc  
$ make -f make_mac.mak  
