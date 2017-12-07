# Git Setup Windows

## Download Git

<http://git-scm.com/download/win>

## Install Git

Select all components.

Select Options:

* Use Nano editor by default
* Use Git from Git Bash only
* Use OpenSSH
* Use OpenSSL
* Checkout Windows-style, commit Unix-style line endings
* Use Windows' default console window
* Enable file system caching
* Enable Git Credential Manager
* Enable symbolic links

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
