**Installation:**

1) clone
`````
git clone git@github.com:volodymyrpartytskyi/vim.git
`````
2) create symlink
````````````
ln -s  ~/.vim/.vimrc ~/.vimrc
````````````
3) add vundle
````````
git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
````````
4) open gvim and enter:
``````````
:BundleInstall
``````````
That’s it!
***
**If you have got warnings in the terminal:**

- _Unable to create Ubuntu Menu Proxy: Timeout was reached_
- _Trying to remove a child that does not believe we are it is parent._

**add** in `~/.bashrc` a lines and **restart** a terminal
``````
function gvim () { (/usr/bin/gvim -f "$@" &>/dev/null &) }
alias gvim='UBUNTU_MENUPROXY= gvim'
``````

***
**[Read wiki](https://github.com/volodymyrpartytskyi/vim/wiki)**
