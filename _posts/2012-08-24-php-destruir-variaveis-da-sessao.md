---
title: "PHP - Destruir variáveis da sessão"
layout: "post"
permalink: "/2012/08/php-destruir-variaveis-da-sessao.html"
uuid: "6698601194361662850"
guid: "tag:blogger.com,1999:blog-871419307951952.post-6698601194361662850"
date: "2012-08-24 17:57:00"
updated: "2012-08-24 17:57:27"
description: 
blogger:
    siteid: "871419307951952"
    postid: "6698601194361662850"
    comments: "0"
categories: [PHP]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#5f5035;'>&lt;?php</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#400000;'>session_start</span><span style='color:#808030;'>(</span><span style='color:#808030;'>)</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#797997;'>$_SESSION</span><span style='color:#808030;'>[</span><span style='color:#0000e6;'>'texto'</span><span style='color:#808030;'>]</span><span style='color:#000000;'> </span><span style='color:#808030;'>=</span><span style='color:#000000;'> </span><span style='color:#0000e6;'>'Olá'</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>unset</span><span style='color:#808030;'>(</span><span style='color:#797997;'>$_SESSION</span><span style='color:#808030;'>[</span><span style='color:#0000e6;'>'texto'</span><span style='color:#808030;'>]</span><span style='color:#808030;'>)</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>echo</span><span style='color:#000000;'> </span><span style='color:#797997;'>$_SESSION</span><span style='color:#808030;'>[</span><span style='color:#0000e6;'>'texto'</span><span style='color:#808030;'>]</span><span style='color:#800080;'>;</span><span style='color:#000000;'> </span><span style='color:#696969;'>// VAI RETORNAR ERRO    </span><span style='color:#000000;'></span><br /><span style='color:#5f5035;'>?></span><br /></pre>
</div>