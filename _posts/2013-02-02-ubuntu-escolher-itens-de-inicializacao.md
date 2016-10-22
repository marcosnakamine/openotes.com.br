---
title: "Ubuntu - Escolher itens de inicialização do sistema"
layout: "post"
permalink: "/2013/02/ubuntu-escolher-itens-de-inicializacao.html"
uuid: "5348146394846529005"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5348146394846529005"
date: "2013-02-02 12:12:00"
updated: "2013-02-02 12:12:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5348146394846529005"
    comments: "0"
categories: [Ubuntu]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
Existem alguns itens que iniciam com o Ubuntu, mas ficam ocultas, para mostrar, digite essa linha no terminal:<br/><pre style="background:#0c1021;color:#f8f8f8">sudo sed -i <span style="color:#61ce3c">'s/NoDisplay=true/NoDisplay=false/g'</span> /etc/xdg/autostart/<span style="color:#fbde2d">*</span>.desktop<br /></pre><br/>Abra o "Aplicativos de sessão" e escolha os itens que quer desabilitar/habilitar.
</div>