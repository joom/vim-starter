vim-starter
===========

Quick starter kit for Vim beginners, including features from modern editors that you might miss when you switch to Vim.

## Installation

After you backup your `~/.vimrc` file and `~/.vim/` folder (this is not important if you haven't used Vim before), you can install this by running this bash line, press enter if you see any error messages:

```bash
echo "runtime vimrc" > ~/.vimrc && mkdir ~/.vim && cd ~/.vim && git clone https://github.com/joom/vim-starter.git . && git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim && vim +PluginInstall
```

You're all set! Enjoy!

## Shortcuts

`<Leader>` is defined as the `\` key by default. `C-x` means Control + x and `M-x` means Meta-x. (*alt* or *option* in modern keyboards) `S-x` means Shift-x.

* `<Leader>y`: Copy to system clipboard
* `<Leader>d`: Cut to system clipboard
* `<Leader>p`: Paste below, from system clipboard
* `<Leader>P`: Paste above, from system clipboard
* `<F5><F5>`: Toggle paste mode. (Not important if you're using the shortcuts above.)
* `<F5>`: Reload Vim settings
* `<Leader>n`: New empty tab.
* `<Space>x`: Remove search highlight.
* `<Leader>]`: Open/Close NERDTree
* `<Leader>[` : Navigate between split views
* `<Tab>`: Buffer list (Normal Mode)
* `C-p`: Fuzzy finder
* ``<Leader>` ``: Swap the positions of the open splits
* `<Space>w`: Next sub-word in a camel cased word
* `<Space>b`: Previous sub-word in a camel cased word
* `<Space>e`: End of sub-word in a camel cased word
* `C-n`: Add the next occurrence of the selection to the multiple cursor selection

Other functions should work as expected. You can define key mappings for your own usage by editing the file `~/.vim/vimrc`, and you are certainly encouraged to do so. That's how you can get the most out of Vim.

If you're looking for a quick tutorial to learn Vim, "[Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)" is a great one.

If copying and pasting with the system clipboard are not working properly, check [this page](http://vim.wikia.com/wiki/Accessing_the_system_clipboard).

## Screenshots

![Screenshot 1](http://i.imgur.com/qEkXK9m.png)

![Screenshot 2](http://i.imgur.com/Elg4TrB.png)

![Screenshot 3](http://i.imgur.com/MSiFlU6.png)
