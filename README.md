vim-starter
===========

Minimal starter kit for Vim beginners.

## Screenshot

![Screenshot](http://i.imgur.com/qEkXK9m.png)

## Installation

After you backup your .vimrc file and .vim folder, you can install this by running this bash line, press enter if you see any error messages:

```bash
echo "runtime vimrc" > ~/.vimrc && mkdir ~/.vim && cd ~/.vim && git clone https://github.com/joom/vimrc.git . && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall
```

You're all set! Enjoy!