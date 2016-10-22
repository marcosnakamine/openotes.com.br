---
title: "JSON - Ajax + MySQL + PHP + JSON"
layout: "post"
permalink: "/2012/12/json-ajax-mysql-php-json.html"
uuid: "5698020146156043654"
guid: "tag:blogger.com,1999:blog-871419307951952.post-5698020146156043654"
date: "2012-12-13 13:52:00"
updated: "2012-12-13 13:54:03"
description: 
blogger:
    siteid: "871419307951952"
    postid: "5698020146156043654"
    comments: "0"
categories: [MySQL, JSON, PHP, jQuery]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
---

<div class="css-full-post-content js-full-post-content">
Arquivo json.php <br /><pre style="background: #0c1021; color: #f8f8f8;">&lt;?php<br />  <span style="color: #aeaeae;">// FAZENDO A CONSULTA NO BANCO</span><br />  $consulta <span style="color: #fbde2d;">=</span> <span style="color: #8da6ce;">mysql_query</span>(<span style="color: #61ce3c;">'<span style="color: #fbde2d;">SELECT</span> <span style="color: #fbde2d;">*</span> <span style="color: #fbde2d;">FROM</span> tabela'</span>);<br />  <span style="color: #aeaeae;">// CRIANDO UMA ARRAY PARA ARMAZENAR OS DADOS DO BANCO</span><br />  $dados <span style="color: #fbde2d;">=</span> <span style="color: #8da6ce;">array</span>();<br />  <span style="color: #aeaeae;">// TRAZER TODOS OS DADOS DO BANCO </span><br /><span style="color: #fbde2d;">  while</span>($linha <span style="color: #fbde2d;">=</span> <span style="color: #8da6ce;">mysql_fetch_assoc</span>($consulta)) {<br />    <span style="color: #aeaeae;">// ARMAZERNAR NA VARIÁVEL $dados</span><br />    <span style="color: #8da6ce;">array_push</span>($dados, $linha);<br />  }<br />  <span style="color: #aeaeae;">// CONVERTENDO A ARRAY PARA O FORMATO JSON E IMPRIMINDO NA TELA</span><br />  <span style="color: #8da6ce;">echo</span> <span style="color: #8da6ce;">json_encode</span>($dados);<br />?&gt;<br /></pre><br />Arquivo index.html <br /><pre style="background: #0c1021; color: #f8f8f8;"><span style="color: #7f90aa;">&lt;<span style="color: #7f90aa;">script</span> <span style="color: #7f90aa;">src</span>=<span style="color: #61ce3c;">"//ajax.googleapis.com/ajax/libs/jquery/1.8.3/jquery.min.js"</span>&gt;&lt;/<span style="color: #7f90aa;">script</span>&gt;</span><br />&lt;<span style="color: #ff6400;">script</span>&gt;<br /><span style="color: #fbde2d;">$</span>(<span style="color: #fbde2d;">function</span>(){<br />  <span style="color: #fbde2d;">$</span>.ajax({<br />    url:<span style="color: #61ce3c;">'json.php'</span>,<br />    dataType:<span style="color: #61ce3c;">'JSON'</span>,<br />    <span style="color: #ff6400;">success</span>:<span style="color: #fbde2d;">function</span>(valores){<br />      <span style="color: #ff6400;">console</span><span style="color: #8da6ce;">.log</span>(valores.nomeDaColuna[<span style="color: #d8fa3c;">0</span>]);<br />    }<br />  });<br />});<br />&lt;/<span style="color: #ff6400;">script</span>&gt;<br /></pre><br />Fontes:<br /><a href="http://tutsmais.com.br/blog/2011/json-ajax-php-jquery/">http://tutsmais.com.br/blog/2011/json-ajax-php-jquery/</a><br /><a href="http://api.jquery.com/jQuery.getJSON/">http://api.jquery.com/jQuery.getJSON/</a><br /><a href="http://api.jquery.com/jQuery.ajax/">http://api.jquery.com/jQuery.ajax/</a>&nbsp; 
</div>