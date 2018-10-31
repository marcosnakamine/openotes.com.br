---
layout: post
title: "[Beginning Docker] Introduction"
date: "2017-04-03 10:00:00 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [virtualbox]
---

# No Linux:

# No Windows:

1. Conecte seu pendrive ou HD externo no computador
1. Aperte win + "r", digite: diskmgmt.msc e clique em OK.
1. Na janela aberta verifique o número do pendrive/HD externo
1. Guarde esse número pra usar mais tarde
1. Abra o prompt de comandos do windows (abra o iniciar e procure por cmd)
1. Digite o seguinte comando substituindo o # pelo número guardado na etapa 4.
1. VBoxManage internalcommands createrawvmdk -filename C:\usb.vmdk -rawdisk \\.\PhysicalDrive#

Abra o VirtualBox em modo administrador

crie uma nova máquina virtual e aponte para o arquivo que acabou de criar (usb.vmdk)

Pronto

Assim que executar sua máquina virtual, ele começará a ler do USB
