Setup
-----

### Bash

In ```~/.bash_profile``` add:

```
if [ -f ~/.bashrc ];
then
    source ~/.bashrc
fi
```

In ```~/.bashrc``` add:

```
. ~/bin/dotfiles/bashrc
```

### Vim

```
ln -nfs ~/bin/dotfiles/vim/vimrc ~/.vimrc
ln -nfs ~/bin/dotfiles/vim/gvimrc ~/.gvimrc
```