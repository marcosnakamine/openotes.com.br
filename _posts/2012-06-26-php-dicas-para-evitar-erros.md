---
title: "PHP - Dicas para evitar erros em IF"
layout: "post"
permalink: "/2012/06/php-dicas-para-evitar-erros.html"
uuid: "5785852141363441985"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5785852141363441985"
date: "2012-06-26 18:03:00"
updated: "2012-06-27 13:44:41"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5785852141363441985"
    comments: "0"
categories: [PHP]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style='color:#000000;background:#ffffff;'><span style='color:#5f5035;'>&lt;?php</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#696969;'>/*SE POR ALGUMA RAZÃO ESQUECERMOS DE COLOCAR "==" EM UM IF, A CONDIÇÃO SERÁ VERDADEIRA </span><br /><span style='color:#696969;'>&#xa0;&#xa0;&#xa0;&#xa0;E PODERÁ SER DIFÍCIL ENCONTRAR O ERRO*/</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#797997;'>$A</span><span style='color:#000000;'> </span><span style='color:#808030;'>=</span><span style='color:#000000;'> </span><span style='color:#008c00;'>10</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>if</span><span style='color:#808030;'>(</span><span style='color:#797997;'>$A</span><span style='color:#000000;'> </span><span style='color:#808030;'>=</span><span style='color:#000000;'> </span><span style='color:#008c00;'>11</span><span style='color:#808030;'>)</span><span style='color:#800080;'>{</span><span style='color:#000000;'> </span><span style='color:#696969;'>// NÃO VAI MOSTRAR ERRO</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>echo</span><span style='color:#000000;'> </span><span style='color:#0000e6;'>'A é igual a 11'</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800080;'>}</span><span style='color:#000000;'></span><br /><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#696969;'>//MAS SE FOR ESCRITA DESTA MANEIRA, RAPIDAMENTE PODEREMOS DETECTAR O ERRO</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>if</span><span style='color:#808030;'>(</span><span style='color:#008c00;'>11</span><span style='color:#000000;'> </span><span style='color:#808030;'>=</span><span style='color:#000000;'> </span><span style='color:#797997;'>$A</span><span style='color:#808030;'>)</span><span style='color:#800080;'>{</span><span style='color:#000000;'> </span><span style='color:#696969;'>// VAI MOSTRAR ERRO</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800000;font-weight:bold; '>echo</span><span style='color:#000000;'> </span><span style='color:#0000e6;'>'A é igual a 11'</span><span style='color:#800080;'>;</span><span style='color:#000000;'></span><br /><span style='color:#000000;'>&#xa0;&#xa0;&#xa0;&#xa0;</span><span style='color:#800080;'>}</span><span style='color:#000000;'></span><br /><span style='color:#5f5035;'>?></span><br /></pre>
</div>