---
title: "PHP - Inserir uma string datetime no MySQL"
layout: "post"
permalink: "/2015/06/php-inserir-uma-string-datetime-no-mysql.html"
uuid: "2136491363134429098"
guid: "tag:blogger.com,1999:blog-871419307951952.post-2136491363134429098"
date: "2015-06-25 20:08:00"
updated: "2015-06-25 20:08:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "2136491363134429098"
    comments: "0"
categories: [MySQL, PHP]
author: 
    name: "Marcos Yoshihiro Nakamine"
    url: "https://plus.google.com/103133083217522235515?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #0c1021; color: #f8f8f8;">&lt;?php<br /><br />$banco <span style="color: #fbde2d;">=</span> <span style="color: #8da6ce;">mysqli_connect</span>(<span style="color: #61ce3c;">'localhost'</span>,<span style="color: #61ce3c;">'usuario'</span>,<span style="color: #61ce3c;">'senha'</span>,<span style="color: #61ce3c;">'banco'</span>);<br /><span style="color: #8da6ce;">mysqli_query</span>($banco,<span style="color: #61ce3c;">'<br />    INSERT INTO tabela <br />        (data) <br />    VALUE <br />        ("'</span><span style="color: #fbde2d;">.</span><span style="color: #8da6ce;">date</span>(<span style="color: #61ce3c;">"Y/m/d h:i:s"</span>,<span style="color: #8da6ce;">strtotime</span>(<span style="color: #61ce3c;">"2015/06/24 23:00:00"</span>))<span style="color: #fbde2d;">.</span><span style="color: #61ce3c;">'")<br />'</span>);<br /><br />?&gt;<br /></pre>
</div>