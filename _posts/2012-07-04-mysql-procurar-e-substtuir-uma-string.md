---
title: "MySQL - Procurar e substituir uma string"
layout: "post"
permalink: "/2012/07/mysql-procurar-e-substtuir-uma-string.html"
uuid: "7858000616504579142"
guid: "tag:blogger.com,1999:blog-871419307951952.post-7858000616504579142"
date: "2012-07-04 14:23:00"
updated: "2012-07-04 17:05:54"
description: 
blogger:
    siteid: "871419307951952"
    postid: "7858000616504579142"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#800000; font-weight:bold; '>UPDATE</span> nome_da_tabela <br /><span style='color:#800000; font-weight:bold; '>SET</span> nome_coluna<span style='color:#808030; '> = </span><span style='color:#800000; font-weight:bold; '>REPLACE</span><span style='color:#808030; '>(</span><br />    nome_coluna<span style='color:#800080; '>,</span><br />    <span style='color:#0000e6; '>'procura isso'</span><span style='color:#800080; '>,</span><br />    <span style='color:#0000e6; '>'substitui por isso'</span><br /><span style='color:#808030; '>)</span><br /></pre>
</div>