# My-vim-setup
A backup repository I created to be able share my vim setup across machines while keeping track of any changes I made.

## Installation
1. Run the following code in your terminal:

```
$ cd
$ git clone https://github.com/rickstaa/.vim.git
$ ln -s -f .vim/.vimrc
```
2. Install Vundle plugin
```
$ git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim
```

3. Run `vim +PluginInstall +qall` in the terminal.

4. Unpack YouCompleteMe Libraries
```
$ sudo apt-get install build-essential cmake
$ sudo apt-get install python-dev python3-dev
$ cd ~/.vim/bundle/YouCompleteMe 
$ ./install.py --clang-completer
```

## Dependencies
* [Vundle plugin manager](https://github.com/VundleVim/Vundle.vim)
* [YouCompleteMe](https://github.com/Valloric/YouCompleteMe)
