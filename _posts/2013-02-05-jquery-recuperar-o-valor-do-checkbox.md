---
title: "jQuery - Recuperar o valor do checkbox quando seu valor for alterado"
layout: "post"
permalink: "/2013/02/jquery-recuperar-o-valor-do-checkbox.html"
uuid: "6810887058595439692"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6810887058595439692"
date: "2013-02-05 17:34:00"
updated: "2013-02-05 17:34:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6810887058595439692"
    comments: "0"
categories: [Javascript, jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background:#0c1021;color:#f8f8f8"><span style="color:#fbde2d">$</span>(<span style="color:#61ce3c">'input'</span>).change(<span style="color:#fbde2d">function</span>(){<br />    <span style="color:#fbde2d">if</span>(<span style="color:#fbde2d">$</span>(this).prop(<span style="color:#61ce3c">'checked'</span>)) {<br />        <span style="color:#8da6ce">alert</span>(<span style="color:#61ce3c">'Checkbox ON'</span>);<br />    } <span style="color:#fbde2d">else</span> {<br />        <span style="color:#8da6ce">alert</span>(<span style="color:#61ce3c">'Checkbox OFF'</span>);<br />    }<br />});<br /></pre>
</div>