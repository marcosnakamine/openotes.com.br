---
title: "Ubuntu - Desativar programas inicializados com o sistema"
layout: "post"
permalink: "/2013/03/ubuntu-desativar-programas.html"
uuid: "5158676275586525945"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5158676275586525945"
date: "2013-03-14 03:55:00"
updated: "2013-03-14 03:55:01"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5158676275586525945"
    comments: "0"
categories: [Ubuntu]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
Primeiro habilite os processos ocultos assim:<br /><pre style="background: #0c1021; color: #f8f8f8;">sudo sed -i <span style="color: #61ce3c;">"s/NoDisplay=true/NoDisplay=false/g"</span> /etc/xdg/autostart/<span style="color: #fbde2d;">*</span>.desktop <br /></pre>Depois abra o <span style="color: orange;">Aplicativos da Sessão</span> e desabilite tudo que você não usa.<br />Fonte: <a href="http://www.ubuntubrsc.com/como-deixar-seu-ubuntu-mais-rapido.html">http://www.ubuntubrsc.com/como-deixar-seu-ubuntu-mais-rapido.html</a>
</div>