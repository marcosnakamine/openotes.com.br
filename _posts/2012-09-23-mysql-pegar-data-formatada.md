---
title: "MySQL - Pegar data formatada"
layout: "post"
permalink: "/2012/09/mysql-pegar-data-formatada.html"
uuid: "8733221241812599924"
guid: "tag:blogger.com,1999:blog-871419307951952.post-8733221241812599924"
date: "2012-09-23 19:29:00"
updated: "2012-09-23 19:29:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "8733221241812599924"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #ffffff; color: black;"><span style="color: maroon; font-weight: bold;">SELECT</span> <br />    tabela<span style="color: #808030;">.</span>campo1<span style="color: purple;">,</span> <br />    tabela<span style="color: #808030;">.</span>campo2<span style="color: purple;">,</span><br />    <span style="color: #400000;">DATE_FORMAT</span><span style="color: #808030;">(</span>campo_do_tipo_date<span style="color: #808030;">,</span><span style="color: maroon;">'</span><span style="color: #007997;">%d</span><span style="color: #0000e6;">/</span><span style="color: #007997;">%m</span><span style="color: #0000e6;">/</span><span style="color: #007997;">%Y</span><span style="color: maroon;">'</span><span style="color: #808030;">)</span> <br /><span style="color: maroon; font-weight: bold;">FROM</span> tabela<br /></pre><br />Fonte: <a href="http://dev.mysql.com/doc/refman/5.5/en/date-and-time-functions.html#function_date-format">http://dev.mysql.com/doc/refman/5.5/en/date-and-time-functions.html#function_date-format</a>
</div>