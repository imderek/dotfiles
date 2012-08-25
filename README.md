dotfiles
========

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

Done.