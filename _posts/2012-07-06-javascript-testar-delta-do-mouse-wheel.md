---
title: "Javascript - Testar delta do mouse wheel"
layout: "post"
permalink: "/2012/07/javascript-testar-delta-do-mouse-wheel.html"
uuid: "5441395601282559157"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5441395601282559157"
date: "2012-07-06 14:03:00"
updated: "2012-07-09 17:17:28"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5441395601282559157"
    comments: "0"
categories: [Javascript]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #ffffff; color: black;"><span style="color: #808030;">&lt;</span>script<span style="color: #808030;">&gt;</span><br />    window<span style="color: #808030;">.</span>addEventListener<span style="color: #808030;">(</span><span style="color: #0000e6;">'DOMMouseScroll'</span><span style="color: #808030;">,</span> testaWheel<span style="color: #808030;">,</span> <span style="color: #0f4d75;">false</span><span style="color: #808030;">)</span><span style="color: purple;">;</span><br />    window<span style="color: #808030;">.</span>onmousewheel <span style="color: #808030;">=</span> testaWheel<span style="color: purple;">;</span><br />    document<span style="color: #808030;">.</span>onmousewheel <span style="color: #808030;">=</span> testaWheel<span style="color: purple;">;</span><br />    <span style="color: maroon; font-weight: bold;">function</span> testaWheel<span style="color: #808030;">(</span>e<span style="color: #808030;">)</span> <span style="color: purple;">{</span><br />        <span style="color: maroon; font-weight: bold;">if</span> <span style="color: #808030;">(</span><span style="color: #808030;">!</span>e<span style="color: #808030;">)</span> <span style="color: dimgrey;">// IE</span><br />            e <span style="color: #808030;">=</span> window<span style="color: #808030;">.</span>event<span style="color: purple;">;</span><br />        <span style="color: maroon; font-weight: bold;">if</span> <span style="color: #808030;">(</span>e<span style="color: #808030;">.</span>wheelDelta<span style="color: #808030;">)</span> <span style="color: purple;">{</span> <span style="color: dimgrey;">// IE / Opera / Chrome</span><br />            delta <span style="color: #808030;">=</span> e<span style="color: #808030;">.</span>wheelDelta<span style="color: #808030;">/</span><span style="color: #008c00;">120</span><span style="color: purple;">;</span><br />        <span style="color: purple;">}</span> <span style="color: maroon; font-weight: bold;">else</span> <span style="color: maroon; font-weight: bold;">if</span> <span style="color: #808030;">(</span>e<span style="color: #808030;">.</span>detail<span style="color: #808030;">)</span> <span style="color: purple;">{</span> <span style="color: dimgrey;">// Firefox</span><br />            delta <span style="color: #808030;">=</span> <span style="color: #808030;">-</span>e<span style="color: #808030;">.</span>detail<span style="color: #808030;">/</span><span style="color: #008c00;">3</span><span style="color: purple;">;</span><br />        <span style="color: purple;">}</span><br />    <span style="color: purple;">}</span><br /><span style="color: #808030;">&lt;</span><span style="color: #808030;">/</span>script<span style="color: #808030;">&gt;</span>&nbsp;</pre><pre style="background: none repeat scroll 0% 0% rgb(255, 255, 255); color: black;"><a name='more'></a></pre>Exemplo:<br/><script>    window.addEventListener('DOMMouseScroll', testaWheel, false);     window.onmousewheel = testaWheel;     document.onmousewheel = testaWheel;     function testaWheel(e) {         if (!e) // IE             e = window.event;         if (e.wheelDelta) { // IE / Opera / Chrome             delta = e.wheelDelta/120;         } else if (e.detail) { // Firefox             delta = -e.detail/3;         }         document.getElementById('delta').value = delta;     } </script>Delta = <input style='text-align:center;' id="delta" type="text" />
</div>