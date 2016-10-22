---
title: "Como alterar o #hash da URL sem rolar a página?"
layout: "post"
permalink: "/2016/03/como-alterar-o-hash-da-url-sem-rolar.html"
uuid: "669038713707475366"
guid: "tag:blogger.com,1999:blog-871419307951952.post-669038713707475366"
date: "2016-03-05 12:57:00"
updated: "2016-03-05 12:57:40"
description: 
blogger:
    siteid: "871419307951952"
    postid: "669038713707475366"
    comments: "0"
categories: [Javascript]
author: 
    name: "Marcos Yoshihiro Nakamine"
    url: "https://plus.google.com/103133083217522235515?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background:#002240;color:#fff"><span style="color:#e1efff">&lt;</span><span style="color:#fd0">script</span><span style="color:#e1efff">></span><br /><span style="color:#ffee80">function</span> <span style="color:#fd0">detectAnchor</span>(){<br />    <span style="color:#ffee80">var</span> yy <span style="color:#ff9d00">=</span> <span style="color:#ff9d00">$</span>(<span style="color:#80ffbb">window</span>).scrollTop()<span style="color:#e1efff">;</span><br />    <span style="color:#ff9d00">if</span> (yy <span style="color:#ff9d00">></span> <span style="color:#ff9d00">$</span>(<span style="color:#3ad900">'</span>#pagina1<span style="color:#3ad900">'</span>).offset().<span style="color:#eb939a">top</span>) {<br />        history.pushState(<span style="color:#ff628c">null</span>, <span style="color:#ff628c">null</span>, <span style="color:#3ad900">'</span>#pagina1<span style="color:#3ad900">'</span>)<span style="color:#e1efff">;</span><br />    } <span style="color:#ff9d00">else</span> <span style="color:#ff9d00">if</span> (yy <span style="color:#ff9d00">></span> <span style="color:#ff9d00">$</span>(<span style="color:#3ad900">'</span>#pagina2<span style="color:#3ad900">'</span>).offset().<span style="color:#eb939a">top</span>) {<br />        history.pushState(<span style="color:#ff628c">null</span>, <span style="color:#ff628c">null</span>, <span style="color:#3ad900">'</span>#pagina2<span style="color:#3ad900">'</span>)<span style="color:#e1efff">;</span><br />    }<br />}<br /><span style="color:#ffb054">setInterval</span>(detectAnchor,<span style="color:#ff628c">1000</span>)<span style="color:#e1efff">;</span><br /><span style="color:#e1efff">&lt;/</span><span style="color:#fd0">script</span><span style="color:#e1efff">></span><br /></pre>
</div>