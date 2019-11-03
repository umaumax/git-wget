# git-wget

download some file or dir from GitHub url

## how to use
```
git-wget https://github.com/umaumax/oressh/blob/master/oressh -O ~/local/bin/
```

## NOTE
* `GIT_WGET_TMP_DIR=~/.config/git-wget/`: use specific directory (not tmp) for cache
* `GIT_WGET_DEBUG`: for debug

## how to install
```
install_path="$HOME/local/bin/git-wget"
wget https://raw.githubusercontent.com/umaumax/git-wget/master/git-wget -O "$install_path"
chmod u+x "$install_path"
```

for zsh completion
```
wget https://raw.githubusercontent.com/umaumax/git-wget/master/_git_wget -O /usr/local/share/zsh/site-functions
```

## FYI
* [sdushantha/gitdir: 📁 Download a single directory/folder from a GitHub repo]( https://github.com/sdushantha/gitdir )
