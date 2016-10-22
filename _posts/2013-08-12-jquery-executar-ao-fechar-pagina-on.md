---
title: "JQuery - Executar ao fechar a página (on unload)"
layout: "post"
permalink: "/2013/08/jquery-executar-ao-fechar-pagina-on.html"
uuid: "7110374724567284525"
guid: "tag:blogger.com,1999:blog-871419307951952.post-7110374724567284525"
date: "2013-08-12 14:52:00"
updated: "2013-08-12 14:52:24"
description: 
blogger:
    siteid: "871419307951952"
    postid: "7110374724567284525"
    comments: "1"
categories: [Javascript, jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background:#0c1021;color:#f8f8f8"><span style="color:#8da6ce">$</span>(<span style="color:#fbde2d">function</span>(){<br />    <span style="color:#fbde2d">$</span>(<span style="color:#8da6ce">window</span>).on(<span style="color:#61ce3c">'beforeunload'</span>,<span style="color:#fbde2d">function</span>(){<br />        <span style="color:#8da6ce">alert</span>(<span style="color:#61ce3c">'fechou'</span>);<br />    });<br />});<br /></pre>
</div>