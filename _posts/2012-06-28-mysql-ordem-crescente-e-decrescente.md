---
title: "MySQL - Ordem crescente e decrescente"
layout: "post"
permalink: "/2012/06/mysql-ordem-crescente-e-decrescente.html"
uuid: "6319303288362086842"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6319303288362086842"
date: "2012-06-28 22:18:00"
updated: "2012-06-28 22:24:12"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6319303288362086842"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#696969; '>/* Ordem crescente: */</span> <br /><span style='color:#800000; font-weight:bold; '>SELECT</span> <span style='color:#808030; '>*</span><br /><span style='color:#800000; font-weight:bold; '>FROM</span> nome_da_tabela <br /><span style='color:#800000; font-weight:bold; '>ORDER</span> <span style='color:#800000; font-weight:bold; '>BY</span> coluna1 <span style='color:#800000; font-weight:bold; '>ASC</span><br /><br /><span style='color:#696969; '>/* Ordem decrescente: */</span><br /><span style='color:#800000; font-weight:bold; '>SELECT</span> <span style='color:#808030; '>*</span><br /><span style='color:#800000; font-weight:bold; '>FROM</span> nome_da_tabela <br /><span style='color:#800000; font-weight:bold; '>ORDER</span> <span style='color:#800000; font-weight:bold; '>BY</span> coluna1 <span style='color:#800000; font-weight:bold; '>DESC</span><br /><br /><span style='color:#696969; '>/* Ordem com mais de uma coluna */</span><br /><span style='color:#800000; font-weight:bold; '>SELECT</span> <span style='color:#808030; '>*</span><br /><span style='color:#800000; font-weight:bold; '>FROM</span> nome_da_tabela <br /><span style='color:#800000; font-weight:bold; '>ORDER</span> <span style='color:#800000; font-weight:bold; '>BY</span> coluna1 <span style='color:#800000; font-weight:bold; '>DESC</span><span style='color:#800080; '>,</span> coluna2 <span style='color:#800000; font-weight:bold; '>ASC</span><br /></pre>
</div>