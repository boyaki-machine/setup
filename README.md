# setup

新しいマシンを構築する際に行う作業手順、必要ファイル達

---
# zsh

## pecoインストール

https://github.com/peco/peco/releases

macはbrew

```shell
brew install peco
```

Linuxは下記のコマンド
```shell
cd /usr/local/src
wget https://github.com/peco/peco/releases/download/v0.5.3/peco_linux_amd64.tar.gz
tar xvzf ./peco_linux_amd64.tar.gz
ln -s /usr/local/src/peco_linux_amd64/peco /usr/local/bin/
```

## .zshrcサンプル

zshrcディレクトリ配下

## 参考 zsh install (mac brew)

```shell
brew install zsh
brew install zsh-completions

sudo vim /etc/shells
...
/usr/local/bin/zsh
...
chsh -s /usr/local/bin/zsh
```

---
# vim

## deinインストール

```shell
curl https://raw.githubusercontent.com/Shougo/dein.vim/master/bin/installer.sh > installer.sh
sh ./installer.sh ~/.vim/dein
```
## .vimrcサンプル

vimディレクトリ配下


---
# tmux

## .tmux.confサンプル

tmuxディレクトリ配下
