---
title: "jQuery - Adicionar e remover um evento de um elemento"
layout: "post"
permalink: "/2013/01/jquery-adicionar-e-remover-um-evento-de.html"
uuid: "6302700547417301808"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6302700547417301808"
date: "2013-01-25 16:30:00"
updated: "2013-01-25 16:30:01"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6302700547417301808"
    comments: "0"
categories: [jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #0c1021; color: #f8f8f8;"><span style="color: #aeaeae;">//Adiciona o evento click na div</span><br /><span style="color: #8da6ce;">$</span>('<span style="color: #ff6400;">div</span>')<span style="color: #8da6ce;">.bind</span>(<span style="color: #61ce3c;">'click'</span>,<span style="color: #fbde2d;">function</span>(){<br />    <span style="color: #aeaeae;">//seu código</span><br />});<br /><br /><span style="color: #aeaeae;">//Remove o evento click da div</span><br /><span style="color: #8da6ce;">$</span>('<span style="color: #ff6400;">div</span>')<span style="color: #8da6ce;">.unbind</span>(<span style="color: #61ce3c;">'click'</span>);<br /></pre><br />Fonte: <a href="http://api.jquery.com/unbind/">http://api.jquery.com/unbind/</a>
</div>