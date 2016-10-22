---
title: "jQuery - Forçar evento click"
layout: "post"
permalink: "/2012/06/jquery-forcar-evento-click.html"
uuid: "675619622570358991"
guid: "tag:blogger.com,1999:blog-871419307951952.post-675619622570358991"
date: "2012-06-29 17:18:00"
updated: "2012-06-29 19:43:07"
description: 
blogger:
    siteid: "871419307951952"
    postid: "675619622570358991"
    comments: "0"
categories: [Javascript, jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#a65700; '>&lt;</span><span style='color:#800000; font-weight:bold; '>script</span><span style='color:#a65700; '>></span><br />    $<span style='color:#808030; '>(</span>document<span style='color:#808030; '>)</span><span style='color:#808030; '>.</span>ready<span style='color:#808030; '>(</span><span style='color:#800000; font-weight:bold; '>function</span><span style='color:#808030; '>(</span><span style='color:#808030; '>)</span><span style='color:#800080; '>{</span><br />        $<span style='color:#808030; '>(</span><span style='color:#0000e6; '>'a'</span><span style='color:#808030; '>)</span><span style='color:#808030; '>.</span>trigger<span style='color:#808030; '>(</span><span style='color:#0000e6; '>'click'</span><span style='color:#808030; '>)</span><span style='color:#800080; '>;</span> <span style='color:#696969; '>// FORÇA O CLIQUE</span><br />    <span style='color:#800080; '>}</span><span style='color:#808030; '>)</span><span style='color:#800080; '>;</span><br /><span style='color:#a65700; '>&lt;/</span><span style='color:#800000; font-weight:bold; '>script</span><span style='color:#a65700; '>></span><br /><span style='color:#a65700; '>&lt;</span><span style='color:#800000; font-weight:bold; '>style</span><span style='color:#a65700; '>></span><br />    <span style='color:#800000; font-weight:bold; '>a</span> <span style='color:#800080; '>{</span><span style='color:#bb7977; font-weight:bold; '>width</span><span style='color:#808030; '>:</span><span style='color:#008c00; '>100</span><span style='color:#006600; '>px</span><span style='color:#800080; '>;</span> <span style='color:#bb7977; font-weight:bold; '>height</span><span style='color:#808030; '>:</span><span style='color:#008c00; '>100</span><span style='color:#006600; '>px</span><span style='color:#800080; '>;</span> <span style='color:#bb7977; font-weight:bold; '>display</span><span style='color:#808030; '>:</span><span style='color:#074726; '>block</span><span style='color:#800080; '>;</span> <span style='color:#bb7977; font-weight:bold; '>background</span><span style='color:#808030; '>:</span><span style='color:#797997; '>red</span><span style='color:#800080; '>;</span><span style='color:#800080; '>}</span><br /><span style='color:#a65700; '>&lt;/</span><span style='color:#800000; font-weight:bold; '>style</span><span style='color:#a65700; '>></span><br /><span style='color:#a65700; '>&lt;</span><span style='color:#800000; font-weight:bold; '>a</span><span style='color:#274796; '> </span><span style='color:#074726; '>href</span><span style='color:#808030; '>=</span><span style='color:#0000e6; '>'javascript:;'</span><span style='color:#274796; '> </span><span style='color:#074726; '>onclick</span><span style='color:#808030; '>=</span><span style='color:#0000e6; '>'alert("Clicou");'</span><span style='color:#a65700; '>></span><span style='color:#a65700; '>&lt;/</span><span style='color:#800000; font-weight:bold; '>a</span><span style='color:#a65700; '>></span><br /></pre>
</div>