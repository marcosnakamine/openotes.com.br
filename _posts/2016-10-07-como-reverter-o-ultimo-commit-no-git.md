---
title: "Como reverter o último commit no git"
layout: "post"
permalink: "/2016/10/como-reverter-o-ultimo-commit-no-git.html"
uuid: "343502746415748415"
guid: "tag:blogger.com,1999:blog-871419307951952.post-343502746415748415"
date: "2016-10-07 01:42:00"
updated: "2016-10-08 17:25:38"
description: 
blogger:
    siteid: "871419307951952"
    postid: "343502746415748415"
    comments: "0"
categories: [GIT]
author: 
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
Ops! Comitei errado.<br /><br />para reverter isso, execute os seguintes comandos:<br /><br />$ git commit -m "Ops, comitei errado!"<br />$ git reset HEAD~<br />&lt;&lt; edite os arquivos se necessário &gt;&gt;<br />$ git add ...<br />$ git commit -c ORIG_HEAD<br /><br />fonte:&nbsp;<a href="http://stackoverflow.com/questions/927358/how-to-undo-last-commits-in-git" target="_blank">stackoverflow.com how-to-undo-last-commits-in-git</a>
</div>