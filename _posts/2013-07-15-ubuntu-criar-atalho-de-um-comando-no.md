---
title: "Ubuntu - Criar atalho de um comando no desktop ou no Unity"
layout: "post"
permalink: "/2013/07/ubuntu-criar-atalho-de-um-comando-no.html"
uuid: "30696137916833819"
guid: "tag:blogger.com,1999:blog-871419307951952.post-30696137916833819"
date: "2013-07-15 13:48:00"
updated: "2013-07-15 13:49:38"
description: 
blogger:
    siteid: "871419307951952"
    postid: "30696137916833819"
    comments: "0"
categories: [Ubuntu]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
No exemplo, vamos criar um atalho para abrir o Nautilus.<br />Crie um arquivo no seu desktop chamado "explorer.desktop" com o seguinte conteúdo:<br /><br />explorer.desktop <br /><pre style="background: #0c1021; color: #f8f8f8;"><span style="color: white;">[Desktop Entry]</span><br /><span style="color: #fbde2d;">Version</span>=1.0<br /><span style="color: #fbde2d;">Name</span>=Abre o Nautilus<br /><span style="color: #fbde2d;">Comment</span>=Simplesmente abre o Nautilus<br /><span style="color: #fbde2d;">Exec</span>=nautilus<br /><span style="color: #fbde2d;">Icon</span>=/usr/share/icons/gnome/32x32/apps/system-file-manager.png<br /><span style="color: #fbde2d;">Terminal</span>=false<br /><span style="color: #fbde2d;">Type</span>=Application<br /><span style="color: #fbde2d;">Categories</span>=Application<span style="color: #aeaeae;">;</span><br /></pre><br />Depois vá no terminal e dê permissão de execução:<br /><pre style="background: #0c1021; color: #f8f8f8;"><span style="color: #8da6ce;">cd</span> <span style="color: #fbde2d;">~</span><span style="color: #61ce3c;">/"Área de Trabalho"</span><br />chmod +x nautilus.desktop<br /></pre><br />Feito isso, você já pode arrastá-lo na sua barra de atalhos do Unity também. <br />Fonte: <a href="https://help.ubuntu.com/community/UnityLaunchersAndDesktopFiles">https://help.ubuntu.com/community/UnityLaunchersAndDesktopFiles</a>
</div>