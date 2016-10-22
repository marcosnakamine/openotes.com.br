---
title: "MySql - Select com expressão regular (regex) entre tabelas"
layout: "post"
permalink: "/2015/06/mysql-select-com-expressao-regular.html"
uuid: "6125652205391283745"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6125652205391283745"
date: "2015-06-24 13:20:00"
updated: "2015-06-24 13:20:59"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6125652205391283745"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Yoshihiro Nakamine"
    url: "https://plus.google.com/103133083217522235515?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #0c1021; color: #f8f8f8;"><span style="color: #fbde2d;">SELECT</span> <span style="color: #fbde2d;">*</span> <br /><span style="color: #fbde2d;">FROM</span> tabela1<br /><span style="color: #fbde2d;">INNER JOIN</span> tabela2 <br />  <span style="color: #fbde2d;">ON</span> (<span style="color: #d8fa3c;">tabela1</span>.<span style="color: #d8fa3c;">colunaCont</span> REGEXP <span style="color: #d8fa3c;">tabela2</span>.<span style="color: #d8fa3c;">colunaRegex</span>)<br /></pre><br />Fonte: <a href="http://stackoverflow.com/a/2964417/1582080">http://stackoverflow.com/a/2964417/1582080</a>
</div>