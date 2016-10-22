---
title: "Como adicionar o nome da banch no terminal bash"
layout: "post"
permalink: "/2016/09/como-adicionar-o-nome-da-banch-no.html"
uuid: "7814717225731796304"
guid: "tag:blogger.com,1999:blog-871419307951952.post-7814717225731796304"
date: "2016-09-28 01:38:00"
updated: "2016-09-28 01:38:51"
description: 
blogger:
    siteid: "871419307951952"
    postid: "7814717225731796304"
    comments: "0"
categories: [terminal, GIT]
author: 
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
resultado será igual a isso:<br /><br /><table cellpadding="0" cellspacing="0" class="tr-caption-container" style="float: left; margin-right: 1em; text-align: left;"><tbody><tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-fb_rFydnD3Y/V-sVbPOaOxI/AAAAAAAAANE/KMgvougFmG86SoTZa9C9MhSBhFgsDxQ6QCLcB/s1600/git-branch-terminal.png" imageanchor="1" style="clear: left; margin-bottom: 1em; margin-left: auto; margin-right: auto;"><img alt="" border="0" src="https://3.bp.blogspot.com/-fb_rFydnD3Y/V-sVbPOaOxI/AAAAAAAAANE/KMgvougFmG86SoTZa9C9MhSBhFgsDxQ6QCLcB/s1600/git-branch-terminal.png" title="terminal mostrando a branch atual do git" /></a></td></tr><tr><td class="tr-caption" style="text-align: center;">resultado final</td></tr></tbody></table><br /><br /><br /><br /><br /><br /><br /><br /><br />Primeiro, abra o seu terminal (bash) e vá até sua home.<br /><code>$ cd</code><br /><br />Caso o arquivo .bash_profiles não exista na sua home, apenas crie-o com o seguinte comando:<br /><code>$ touch .bash_profiles</code><br />Caso já exista, abra-o com o seu editor de texto favorito e adicione as seguintes linhas:<br /><code><blockquote class="tr_bq" style="color: #333333; font-family: Menlo, Monaco, &quot;Courier New&quot;, &quot;DejaVu Sans Mono&quot;, &quot;Bitstream Vera Sans Mono&quot;, monospace; font-size: 0.95rem; line-height: 1.75; overflow-x: auto;"># Git branch in prompt.<br />parse_git_branch() {<br />    git branch 2&gt; /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'<br />}<br />export PS1="\u@\h \W\[\033[32m\]\$(parse_git_branch)\[\033[00m\] $ "</blockquote></code><br />Salve e volte para o terminal.<br />Agora recarregue o arquivo .bash_profile para que o terminal interprete as novas linhas com o seguinte comando:<br /><code>$ source .bash_profile</code>
</div>