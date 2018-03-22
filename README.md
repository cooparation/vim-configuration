# my-vim-configuration

2016.05.03

##Usage
* cp -fr vim.lsj ~/.vim
* cp vimrc.lsj ~/.vimrc

## Check Status
* ```vim --version | grep clip*```   
* if clipboard and xterm_clipboard is supported with '+', then system
clipboard could be work, or you may be install vim with follows:   
* sudo apt-get install vim vim-scripts vim-gtk vim-gnome

## Deps
* nerdtree https://github.com/scrooloose/nerdtree.git
* cpp autocomplete, need to download the cpp_src to vim and ctags the src, details to see http://blog.csdn.net/doc_sgl/article/details/47205779
* YouCompleteMe: details to see https://github.com/Valloric/YouCompleteMe.git
* ctrlp: https://github.com/ctrlpvim/ctrlp.vim, Full path fuzzy file, buffer, mru, tag, ... finder for Vim
