---
layout: post
title: "Useful GIT Commands"
date: "2017-01-24 11:01:43 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [GIT]
---

Segue uma lista de vários comandos úteis para o dia a dia usando GIT pela linha de comandos (CLI).

Sincronizar um fork

``` terminal
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
```

Git force pull to overwrite local files

``` terminal
$ git fetch --all
$ git reset --hard origin/master
$ git pull origin master
```
