---
layout: post
title: "How to configure Raspberry PI with hidden network"
date: "2017-01-17 00:55:43 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [Raspberry PI]
---

Para configurar a Raspberry PI em uma rede sem fio oculta, basta logo após ligar a rasp, executar o comando:

``` terminal
sudo iwlist wlan0 scan essid *seuSSID*
```

Se retornar as informações da sua rede, siga para o próximo passo.

Adicione a seguinte linha no arquivo __/etc/wpa_supplicant/wpa_supplicant.conf__

``` terminal
scan_ssid=1
```

Pronto, a sua Raspberry PI estará pronta pra conectar na rede oculta.
