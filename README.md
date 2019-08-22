# syntastic-coala

**Installation Instructions:**

There are 3 ways to install this plugin to begin using it with vim.

**1) Manually (for vim)**

1) Navigate to your `.vim` directory

2) Create a `bundle` directory inside your `.vim` folder

3) `git clone https://github.com/RohanVB/syntastic-coala.git` inside the bundle directory

4) Find your vim runtimepath. This can be done by running `:set runtimepath?` inside the vim editor

5) Edit `~/.vimrc` to contain `set runtimepath^=~/.vim/bundle/ctrlp.vim` (replace it to what your runtimepath is)

6) Reload your `~/.vimrc` by `:source ~/.vimrc`


**2) Using `vim-plug` (for vim)**

Add `Plug https://github.com/RohanVB/syntastic-coala.git` to the vim-plug section of your `~/.vimrc`


**3) Using `vim-plug` (for neovim)**

Add `Plug https://github.com/RohanVB/syntastic-coala.git` to the vim-plug section of `~/.config/nvim/init.vim`


![coala](https://files.gitter.im/coala/coala/IRBP/Screen-Shot-2017-04-25-at-12.45.59-PM.png)
