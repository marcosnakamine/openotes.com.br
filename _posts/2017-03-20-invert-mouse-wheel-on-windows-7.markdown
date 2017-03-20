---
layout: post
title: "Invert Mouse Wheel on Windows 7"
date: "2017-03-20 08:59:22 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [windows]
---

Para inverter a rolagem do mouse faça os seguintes passos:

1. Procure o Hardware ID do mouse

  - Vá até o painel de controle do mouse
  - Selecione a aba “Hardware”
  - Clique no botão “Propriedades”
  - Selecione a aba “Detalhes”
  - Da lista de opções, selecione o “Hardware IDs”
  - Salve a entrada VID*** ( exemplo: VID_045E&PID_0039 )
  - Procure e mude a configuração correspondente nas configurações do registro

2. Abra o regedit.exe

  - Abra a chave: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\HID
  - Aqui você precisa encontrar a entrada do hardware ID do seu mouse
  - Dentro de todas as sub-chaves do seu hardware id, procure pela chave "DeviceParameters" e mude o valor da chave "FlipFlopWheel" do 0 para 1

3. Faça funcionar
  - Desconecte o mouse do seu computador
  - E conecte novamente
