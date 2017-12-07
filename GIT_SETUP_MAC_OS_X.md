# Git Setup Mac OS X

## Install Git

### Download and install XCode

<https://developer.apple.com/xcode/>

### Install Homebrew

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

Insert Homebrew directory at the top of the PATH by adding the
following line to the bottom of your ~/.profile file (create it if it
does not exist):

```shell
export PATH=/usr/local/bin:/usr/local/sbin:$PATH
```

Open a new terminal to complete the PATH modification or run:

```shell
source ~/.profile
```

### Install Git Using Homebrew

```shell
brew install git
```

## Setup Git

### Set username and email address for every repository

```shell
git config --global user.name "Mona Lisa"
git config --global user.email "email@example.com"
```

### Set username and email address for a single repository

```shell
git config user.name "Mona Lisa"
git config user.email "email@example.com"
```
