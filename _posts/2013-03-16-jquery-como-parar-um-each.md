---
title: "jQuery - Como parar um each ?"
layout: "post"
permalink: "/2013/03/jquery-como-parar-um-each.html"
uuid: "184222980099106641"
guid: "tag:blogger.com,1999:blog-871419307951952.post-184222980099106641"
date: "2013-03-16 13:59:00"
updated: "2013-03-16 13:59:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "184222980099106641"
    comments: "0"
categories: [jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #0c1021; color: #f8f8f8;"><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">script</span> <span style="color: #7f90aa;">src</span>=<span style="color: #61ce3c;">"http://code.jquery.com/jquery-latest.js"</span>&gt;&lt;/<span style="color: #7f90aa;">script</span>&gt;</span><br />&lt;<span style="color: #ff6400;">script</span>&gt;<br />    <span style="color: #fbde2d;">$</span>(<span style="color: #61ce3c;">'div'</span>).each(<span style="color: #fbde2d;">function</span>(index){ <span style="color: #aeaeae;">// VARRE TODAS AS DIVS</span><br />        <span style="color: #ff6400;">console</span><span style="color: #8da6ce;">.log</span>(index); <span style="color: #aeaeae;">// MOSTRA O ÍNDICE DO ELEMENTO NO CONSOLE DO NAVEGADOR</span><br />        <span style="color: #fbde2d;">if</span>(index <span style="color: #fbde2d;">==</span> <span style="color: #d8fa3c;">3</span>) {<br />            <span style="color: #fbde2d;">return</span> <span style="color: #d8fa3c;">false</span>; <span style="color: #aeaeae;">// PÁRA O LOOP</span><br />        }<br />    })<br />&lt;/<span style="color: #ff6400;">script</span>&gt;<br /><br /><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">div</span>&gt;&lt;/<span style="color: #7f90aa;">div</span>&gt;</span><br /><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">div</span>&gt;&lt;/<span style="color: #7f90aa;">div</span>&gt;</span><br /><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">div</span>&gt;&lt;/<span style="color: #7f90aa;">div</span>&gt;</span><br /><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">div</span>&gt;&lt;/<span style="color: #7f90aa;">div</span>&gt;</span><br /><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">div</span>&gt;&lt;/<span style="color: #7f90aa;">div</span>&gt;</span><br /></pre>Fonte: <a href="http://api.jquery.com/each/">http://api.jquery.com/each/</a>
</div>