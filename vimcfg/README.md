### If ~/.vimrc and ~/.vim/ exist  

mv ~/.vimrc ~/.vimrc.old
mv ~/.vim ~/.vim.old

### do following steps

```bash  
mv something/vimcfg/vimrc ~/.vimrc  
mkdir ~/.vim
mv something/vimcfg/colors ~/.vim/
```


git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
vim +BundleInstall +qall
