---
title: "MySQL - Verificar se um elemento existe"
layout: "post"
permalink: "/2012/09/mysql-verificar-se-um-elemento-existe.html"
uuid: "6860473016268669808"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6860473016268669808"
date: "2012-09-05 14:40:00"
updated: "2012-09-05 14:40:22"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6860473016268669808"
    comments: "0"
categories: [MySQL]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #ffffff; color: black;"><span style="color: maroon; font-weight: bold;">SELECT</span> <span style="color: maroon; font-weight: bold;">EXISTS</span><span style="color: #808030;">(</span><span style="color: maroon; font-weight: bold;">SELECT</span> <span style="color: purple;">*</span> <span style="color: maroon; font-weight: bold;">FROM</span> table1 <span style="color: maroon; font-weight: bold;">WHERE</span> <span style="color: #808030;">.</span><span style="color: #808030;">.</span><span style="color: #808030;">.</span><span style="color: #808030;">)</span><br /></pre> Fonte: <a href="http://stackoverflow.com/questions/1676551/best-way-to-test-if-a-row-exists-in-a-mysql-table">http://stackoverflow.com/questions/1676551/best-way-to-test-if-a-row-exists-in-a-mysql-table</a>
</div>