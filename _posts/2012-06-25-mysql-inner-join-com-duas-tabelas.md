---
title: "MySQL - INNER JOIN com 2 tabelas"
layout: "post"
permalink: "/2012/06/mysql-inner-join-com-duas-tabelas.html"
uuid: "8434581041003865752"
guid: "tag:blogger.com,1999:blog-871419307951952.post-8434581041003865752"
date: "2012-06-25 20:33:00"
updated: "2012-06-28 13:00:08"
description: 
blogger:
    siteid: "871419307951952"
    postid: "8434581041003865752"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#800000; font-weight:bold; '>SELECT</span> <br />    tabela1<span style='color:#808030; '>.</span>coluna1<span style='color:#800080; '>,</span> <br />    tabela1<span style='color:#808030; '>.</span>coluna2<span style='color:#800080; '>,</span> <br />    tabela2<span style='color:#808030; '>.</span>col1<span style='color:#800080; '>,</span> <br />    tabela2<span style='color:#808030; '>.</span>col2 <br /><span style='color:#800000; font-weight:bold; '>FROM</span> tabela1 <br /><span style='color:#800000; font-weight:bold; '>INNER</span> <span style='color:#800000; font-weight:bold; '>JOIN</span> tabela2 <br /><span style='color:#800000; font-weight:bold; '>ON</span> tabela1<span style='color:#808030; '>.</span>coluna1 <span style='color:#808030; '>=</span> tabela2<span style='color:#808030; '>.</span>col1<br /></pre>
</div>