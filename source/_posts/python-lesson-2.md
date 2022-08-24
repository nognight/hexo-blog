---
title: Python Starter lesson-2
date: 2022-08-24 25:30:22
tags: python
---

# Install
## why we use package manager
- 

### windows we choose scoop

```shell

Set-ExecutionPolicy RemoteSigned -Scope CurrentUser # Optional: Needed to run a remote script the first time

irm get.scoop.sh | iex

scoop bucket add versions

scoop install python310

python3 -V

```

### mac we choose brew

```shell

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

brew install python

python3 -V

```


### for linux
- redhat -> yum
- debain -> apt-get
- suse -> yast2


# Redo what Hello python
- Python is a popular programming language and released in 1991.
- Now is Python3

#  start development

## how to use pip

```shell
pip3 install xxxxxx
```

## how to use IDE

```shell
scoop install pycharm
```

```shell
brew install pycharm
```

## read data from excel

## diagram
![](/images/lesson-2.png)










