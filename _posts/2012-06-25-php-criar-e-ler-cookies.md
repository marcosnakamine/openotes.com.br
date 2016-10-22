---
title: "PHP - Criar e ler cookies"
layout: "post"
permalink: "/2012/06/php-criar-e-ler-cookies.html"
uuid: "1174565356869151265"
guid: "tag:blogger.com,1999:blog-871419307951952.post-1174565356869151265"
date: "2012-06-25 18:02:00"
updated: "2012-06-25 18:02:32"
description: 
blogger:
    siteid: "871419307951952"
    postid: "1174565356869151265"
    comments: "0"
categories: [PHP]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#5f5035;'>&lt;?php</span><span style='color:#000000;'> </span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#400000;'>setcookie</span><span style='color:#808030;'>(</span><span style='color:#0000e6;'>'biscoito'</span><span style='color:#808030;'>,</span><span style='color:#0000e6;'>'chocolate'</span><span style='color:#808030;'>)</span><span style='color:#800080;'>;</span><span style='color:#000000;'> </span><span style='color:#696969;'>// CRIA O COOKIE</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>echo</span><span style='color:#000000;'> </span><span style='color:#797997;'>$_COOKIE</span><span style='color:#808030;'>[</span><span style='color:#0000e6;'>'biscoito'</span><span style='color:#808030;'>]</span><span style='color:#800080;'>;</span><span style='color:#000000;'> </span><span style='color:#696969;'>// RETORNA O VALOR DO COOKIE CRIADO</span><span style='color:#000000;'></span><br /><span style='color:#5f5035;'>?></span><br /></pre>
</div>