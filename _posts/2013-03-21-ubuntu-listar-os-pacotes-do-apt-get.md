---
title: "Ubuntu - Listar os pacotes do apt-get pelo apt-cache search"
layout: "post"
permalink: "/2013/03/ubuntu-listar-os-pacotes-do-apt-get.html"
uuid: "8824596558311165157"
guid: "tag:blogger.com,1999:blog-871419307951952.post-8824596558311165157"
date: "2013-03-21 15:05:00"
updated: "2013-03-21 15:05:00"
description: 
blogger:
    siteid: "871419307951952"
    postid: "8824596558311165157"
    comments: "0"
categories: [Ubuntu]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
<pre style="background: #0c1021; color: #f8f8f8;">apt-cache search alguma_coisa<br /><br /><span style="color: #aeaeae;">#por exemplo, vamos supor que você tenha esquecido </span><br /><span style="color: #aeaeae;">#o nome de um plugin do Geany (uma IDE muito boa pra php, html, ...)</span><br />apt-cache search geany<br /><br /><span style="color: #aeaeae;">#listará os itens abaixo</span><br /><br /><span style="color: #aeaeae;">#geany - fast and lightweight IDE</span><br /><span style="color: #aeaeae;">#geany-common - fast and lightweight IDE -- common files</span><br /><span style="color: #aeaeae;">#geany-plugin-addons - miscellanous plugins for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-codenav - code navigation plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-debugger - debugger plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-doc - documentation plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-extrasel - extra selection plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-gdb - GDB plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-gendoc - documentation generation plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-gproject - gproject plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-insertnum - number inserting plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-latex - improved LaTeX support plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-lipsum - Lorem Ipsum generator plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-lua - Lua scripting plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-macro - macro plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-numberedbookmarks - numbered bookmarks plugin for #Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-pg - pg plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-prettyprinter - XML pretty printer for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-prj - alternative project manager for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-sendmail - mailer plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-shiftcolumn - text column shifting plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-spellcheck - spellcheck plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-tableconvert - table convert plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-treebrowser - tree browser plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-updatechecker - update checker plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-vc - VCS plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-webhelper - web helper plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugin-xmlsnippets - XMLSnippets plugin for Geany</span><br /><span style="color: #aeaeae;">#geany-plugins - set of plugins for Geany</span><br /><span style="color: #aeaeae;">#geany-plugins-common - set of plugins for Geany (translations)</span><br /><br /><span style="color: #aeaeae;">#depois é só dar um install</span><br />sudo apt-get install geany-plugins-common<br /></pre>
</div>