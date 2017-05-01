## some packages and tools needed to install after install a new system for ubuntu or debian

###
```shell
sudo apt-get install openssl libreadline-dev zlib1g zlib1g-dev libssl-dev libyaml-dev \
 autoconf libc6-dev ncurses-dev automake libtool bison build-essential git-core curl \
zlib1g-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev python-software-properties \
cmake imagemagick libmagickcore-dev imagemagick-common libmagickwand-dev libcurl4-openssl-dev \
libicu-dev libjemalloc-dev libmysqlclient-dev mysql-server tree redis-server strace \
postgresql firefox atom vscode sublime-text sublime-text-dev autojump libboost-all-dev \
libevent-2.0-5 libevent-dev zsh emacs clang llvm docker.io virtualbox vagrant sysv-rc-conf \
htop iotop sysstat qt5-default qt5-qmake qt5-doc qttools5-dev-tools libegl1-mesa-dev libpq-dev \
libqt5sql5-sqlite libqt5sql5-mysql libqt5sql5-psql libssh2-1-dev ruby ruby-dev ansible
```

### zsh
```shell
git clone git://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh
sudo chsh -s $(which zsh)
```

### vim
```shell
tar xf vim.tgz
```

### emacs
```shell
tar xf emacs.tgz
```

### rvm
```shell
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
curl -sSL https://get.rvm.io | bash -s stable
mkdir -p ~/.rvm/user
echo "ruby_url=https://cache.ruby-china.org/pub/ruby" > ~/.rvm/user/db
source ~/.rvm/scripts/rvm
rvm install ruby --latest
```

