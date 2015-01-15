## Setup

Clone repo to `~/bin/dotfiles`:

```
mkdir ~/bin
cd ~/bin
git clone git@github.com:imderek/dotfiles.git
```

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
