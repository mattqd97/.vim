# This is my Vim config

Still under construction (and probably always will be)

## How to use
1. cd to $HOME
```
cd ~
```
2. Clone this repo
```
git clone https://github.com/mattqd97/.vim.git
```
3. Open the vimrc in the repo
```
vim ~/.vim/vimrc
```
4. Run `:PlugInstall` in Vim  
  4.1 **Note**: If you do not want to install YouCompleteMe, comment out `Plug 'Valloric/YouCompleteMe'` (line 119)  
5. Finish installing [YouCompleteMe](https://github.com/ycm-core/YouCompleteMe) for line-completion  
  6.1 [macOS Installation](https://github.com/ycm-core/YouCompleteMe#macos)  
  6.2 [Linux Installation](https://github.com/ycm-core/YouCompleteMe#linux-64-bit)  
6. (On older Vim versions) Add `runtime vimrc` to ~/.vimrc  

