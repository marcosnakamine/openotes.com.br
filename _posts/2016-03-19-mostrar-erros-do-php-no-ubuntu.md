---
title: "Mostrar erros do PHP no Ubuntu"
layout: "post"
permalink: "/2016/03/mostrar-erros-do-php-no-ubuntu.html"
uuid: "3214448388800221634"
guid: "tag:blogger.com,1999:blog-871419307951952.post-3214448388800221634"
date: "2016-03-19 20:08:00"
updated: "2016-03-19 20:08:50"
description: 
blogger:
    siteid: "871419307951952"
    postid: "3214448388800221634"
    comments: "0"
categories: [Apache, Ubuntu, PHP]
author: 
    name: "Marcos Yoshihiro Nakamine"
    url: "https://plus.google.com/103133083217522235515?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
---

<div class="css-full-post-content js-full-post-content">
<h3>1ª Solução </h3><pre style="background: #002240; color: white;">sudo nano /etc/php5/apache2/php.ini<br /></pre><br />Procure por display_errors (Aperte CTRL+W)<br />Altere para:<br /><pre style="background: #002240; color: white;"><span style="color: #ff9d00;">display_errors</span> <span style="color: #e1efff;">=</span> On<br /></pre><br /><h3>2ª Solução&nbsp;</h3>Procure o php.ini correto com o comando:<br /><pre style="background: #002240; color: white;">php<span style="color: #ff9d00;"> -</span><span style="color: #ff9d00;">i</span><span style="color: #ff9d00;">|</span>grep php.ini<br /></pre><br />E siga os mesmos passos da primeira solução<br /><br /><h3>3ª Solução</h3><pre style="background: #002240; color: white;">sudo nano /etc/apache2/sites-enabled/000-default.conf <br /></pre><br />Adicione isso no fim do arquivo<br /><pre style="background: #002240; color: white;"><span style="color: #ff9d00;">&lt;</span>IfModule mod_php5.c<span style="color: #ff9d00;">&gt;</span><br />    php_admin_flag engine <span style="color: #ff9d00;">on</span><br />    php_admin_value display_errors <span style="color: #ff9d00;">on</span><br />    php_admin_flag ini_set <span style="color: #ff9d00;">on</span><br /><span style="color: #ff9d00;">&lt;</span><span style="color: #ff9d00;">/</span>IfModule<span style="color: #ff9d00;">&gt;</span><br /></pre><br /><br />Fontes:<br /><a href="http://askubuntu.com/a/578562/150323">http://askubuntu.com/a/578562/150323</a><br /><br /><a href="http://www.linuxquestions.org/questions/linux-software-2/php-ini-display_errors-%3D-off-not-respected-796299/">http://www.linuxquestions.org/questions/linux-software-2/php-ini-display_errors-%3D-off-not-respected-796299/</a>
</div>