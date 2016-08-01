---
title: How to build blog with hexo on github
date: 2016-08-01 10:17:42
tags: Help Documents
---


## What is Hexo?

Check [documentation](https://hexo.io/docs/) for knowledge.

## Requirements

Hexo is runing based dependency.We should have a couple of other things installed first:
+ [Git](https://git-scm.com)
+ [Node.js](https://nodejs.org)


## Install Git
+ Windows: Download & install [git](https://git-scm.com/downloads).
+ Linux (Ubuntu, Debian): sudo apt-get install git-core
+ Linux (Fedora, Red Hat, CentOS): sudo yum install git-core

## Install Node.js
+ Window: Download & intall [Node.js](https://nodejs.org/en/download/)
+ Linux: nvm install stable

> Notes:
> System environment should be setted.
> npm config set prefix "C:\Program Files\nodejs\node_global".
> npm config set cache "C:\Program Files\nodejs\node_cache".
> Append user environment variable Path with "C:\Program Files\nodejs\node_cache".
> New a system environment variable named NODE_PATH and set value "C:\Program Files\nodejs\node_global\node_modules".
> Fource environment effective.

## Install Hexo
Once all the requirements are installed, you can install Hexo with npm.

Installing Hexo is quite easy. However, you do need to have a couple of other things installed first:

``` bash
$ npm install -g hexo-cli
```

Onece Hexo is installed,run the following commands to initialise Hexo in the target <folder>.

``` bash
$ hexo init <folder>
```

## Install Theme

``` bash
$ git clone https://github.com/wuchong/jacman.git themes/jacman
```

## Config _config.yml



## Basic Usage

### Creating a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server


``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)


### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/deployment.html)




