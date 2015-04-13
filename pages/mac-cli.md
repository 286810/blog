# 常用 CLI 应用

## HomeBrew & HomeBrew Cask

Homebrew 是 Mac 下最好用的包管理器，推荐所有控制台应用都尽可能使用 brew 管理。

安装 [HomeBrew](http://brew.sh)：

```sh
ruby -e “$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)”
```

Homebrew Cask 是 Homebrew 的插件，作为 Homebrew 在 GUI 应用上的补充。

安装 [HomeBrew Cask](https://github.com/caskroom/homebrew-cask)：

```sh
brew install caskroom/cask/brew-cask
```


## zsh & oh-my-zsh!

被称为终极 shell 也没什么问题。Mac 已经预装了 zsh ，只需要安装 `oh-my-zsh!` 即可：

```sh
curl -L https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh | sh
```

或者：

```sh
wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O - | sh
```


## tree

显示目录的树状图



## htop

进程管理器，比自带的 top 要强大许多。



## autojumps

在常用目录间快速跳转，命令是 `j`。



## IPython

提供更强大的 Python REPL 环境，配合 IPython Notebook 能提供强大的 web 执行环境。



## ag

文件查找命令，类似于 `ack`。



## git

最流行的分布式代码管理工具。



## pip & gem & npm & cnpm

pip 以外的所有 Python 应用都应该使用 pip 来安装！

gem 是 Ruby 的包管理器，安装 compass / puppet / vagrant 等 Ruby 系应用时离不开 gem。

npm 是 node.js 包管理器，cnpm 是 淘宝提供的 npm 替代品。



## pgcli

[pgcli](https://github.com/amjith/pgcli) 是控制台中的 PostgreSQL 管理工具，功能强大！
推荐使用 brew 安装：

```sh
brew install pgcli
```

不过，由于 pgcli 是 Python 应用，你也可以使用 ``pip`` 或者 ``easy_install`` 安装：

```sh
pip install pgcli
```


## uwsgi & gunicorn

提供 WSGI 支持的 web 服务器。



## sphinx

Python 社区的文档管理标准，著名的文档托管服务 [ReadTheDocs](http://rtfd.org) 服务就是基于其搭建，
支持 i18n，配合 Python 注释自动生成非常方便。



## virtualenv

提供 Python 虚拟环境的隔离。


## VirtualEnvWrapper

virtualenv 命令复杂，目录的管理也比较混乱，VirtualEnvWrapper 是在这之上的一层封装。


## tmux

控制台中的标签页管理工具以及分屏管理工具。
