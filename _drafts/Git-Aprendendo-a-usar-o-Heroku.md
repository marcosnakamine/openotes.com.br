---
title: "Git - Aprendendo a usar o Heroku"
layout: "post"
permalink: "/Git-Aprendendo-a-usar-o-Heroku.html"
uuid: "931319352369521574"
guid: "tag:blogger.com,1999:blog-871419307951952.post-931319352369521574"
date: "2013-07-05 20:02:00"
updated: "2013-07-05 20:02:57"
description: 
blogger:
    siteid: "871419307951952"
    postid: "931319352369521574"
    comments: "0"
categories: [GIT]
author: 
    name: "Marcos Nakamine"
    url: "https://plus.google.com/117200895427105171614?rel=author"
    image: "//lh6.googleusercontent.com/-6t0lck2nDvI/AAAAAAAAAAI/AAAAAAAAOBw/_9ON3AiIr48/s32-c/photo.jpg"
published: "false"
---

<div class="css-full-post-content js-full-post-content">
git init -&gt; inicia o git<br />git remote update -&gt; atualiza o repositório<br />git commit -m "comentárop" -&gt; faz um commit<br />git add arquivo.html -&gt; adiciona o arquivo no git <br /><br />heroku create -&gt; cria o repositório online <br />heroku keys:clear -&gt; deleta todas as chaves<br />heroku keys:add -&gt; cria uma chave (serve para possibilitar o push)<br />git push heroku master -&gt; envia os arquivos para o repositório online<br /><br /><br />exemplo do heroku<br /><ol><li><code class="prompt">git clone git://github.com/heroku/<span class="faux-select"><span class="replace-me">ruby</span>        </span>-sample.git</code></li><li><code class="prompt">cd&nbsp;<span class="replace-me">ruby</span>-sample</code></li><li><code class="prompt">heroku create </code></li><li><code class="prompt">git push heroku master</code></li><li><code class="prompt">heroku open</code></li></ol><br /><br />Fontes:<br />http://stackoverflow.com/questions/14713845/git-push-heroku-master-permission-denied-publickey?lq=1<br />http://stackoverflow.com/questions/14342553/git-push-heroku-master-permission-denied<br />http://stackoverflow.com/questions/3481973/heroku-error-permission-denied-public-key<br />https://devcenter.heroku.com/articles/keys<br />http://www.youtube.com/watch?v=L2YlEIMrGxA
</div>