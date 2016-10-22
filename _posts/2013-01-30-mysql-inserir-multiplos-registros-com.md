---
title: "MySQL - Inserir múltiplos registros com uma linha"
layout: "post"
permalink: "/2013/01/mysql-inserir-multiplos-registros-com.html"
uuid: "5039734206889463356"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5039734206889463356"
date: "2013-01-30 18:02:00"
updated: "2013-01-30 18:02:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5039734206889463356"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background:#0c1021;color:#f8f8f8"><span style="color:#fbde2d">INSERT INTO</span> nome_da_tabela (<br />    coluna1,<br />    coluna2,<br />    coluna3<br />) VALUE (<br />    <span style="color:#61ce3c">"valor1"</span>,<br />    <span style="color:#61ce3c">"valor2"</span>,<br />    <span style="color:#61ce3c">"valor3"</span><br />),<br />(<br />    <span style="color:#61ce3c">"valor4"</span>,<br />    <span style="color:#61ce3c">"valor5"</span>,<br />    <span style="color:#61ce3c">"valor6"</span><br />),<br />(<br />    <span style="color:#61ce3c">"valor7"</span>,<br />    <span style="color:#61ce3c">"valor8"</span>,<br />    <span style="color:#61ce3c">"valor9"</span><br />),<br />(<br />    <span style="color:#61ce3c">"valor10"</span>,<br />    <span style="color:#61ce3c">"valor11"</span>,<br />    <span style="color:#61ce3c">"valor12"</span><br />)<br /></pre>
</div>