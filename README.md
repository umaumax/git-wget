# git-wget

download some file or dir from GitHub url

## how to use
``` bash
git-wget https://github.com/umaumax/oressh/blob/master/oressh -O ~/local/bin/
```

## NOTE
* `GIT_WGET_TMP_DIR=~/.config/git-wget/`: use specific directory (not tmp) for cache
* `GIT_WGET_DEBUG`: for debug

## how to install
``` bash
install_path="$HOME/local/bin/git-wget"
wget https://raw.githubusercontent.com/umaumax/git-wget/master/git-wget -O "$install_path"
chmod u+x "$install_path"
```

for zsh completion
``` bash
wget https://raw.githubusercontent.com/umaumax/git-wget/master/_git_wget -O /usr/local/share/zsh/site-functions
```

## TODO
* check git clone with single branch mode

## FYI
* [sdushantha/gitdir: 📁 Download a single directory/folder from a GitHub repo]( https://github.com/sdushantha/gitdir )
* [Git で shallow clone するときに全ブランチの最新履歴を取得する]( https://zenn.dev/snowcait/articles/d44d6b2bed2e4b29ada4 )
