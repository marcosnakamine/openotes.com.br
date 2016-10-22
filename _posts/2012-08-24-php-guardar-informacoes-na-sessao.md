---
title: "PHP - Guardar informações na sessão"
layout: "post"
permalink: "/2012/08/php-guardar-informacoes-na-sessao.html"
uuid: "8469321911488112659"
guid: "tag:blogger.com,1999:blog-871419307951952.post-8469321911488112659"
date: "2012-08-24 17:55:00"
updated: "2012-08-24 17:55:28"
description: 
blogger:
    siteid: "871419307951952"
    postid: "8469321911488112659"
    comments: "0"
categories: [PHP]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #ffffff; color: black;"><span style="color: #5f5035;">&lt;?php</span><span style="color: black;"></span><br /><span style="color: black;">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="color: #400000;">session_start</span><span style="color: #808030;">(</span><span style="color: #808030;">)</span><span style="color: purple;">;</span><span style="color: black;"></span><br /><span style="color: black;">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="color: #797997;">$_SESSION</span><span style="color: #808030;">[</span><span style="color: #0000e6;">'texto'</span><span style="color: #808030;">]</span><span style="color: black;"> </span><span style="color: #808030;">=</span><span style="color: black;"> </span><span style="color: #0000e6;">'Olá'</span><span style="color: purple;">;</span><span style="color: black;"></span><br /><span style="color: black;">&nbsp;&nbsp;&nbsp;&nbsp;</span><span style="color: maroon; font-weight: bold;">echo</span><span style="color: black;"> </span><span style="color: #797997;">$_SESSION</span><span style="color: #808030;">[</span><span style="color: #0000e6;">'texto'</span><span style="color: #808030;">]</span><span style="color: purple;">;</span><span style="color: black;">    </span><br /><span style="color: #5f5035;">?&gt;</span><br /></pre>
</div>