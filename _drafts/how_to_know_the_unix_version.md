
---
layout: post
title: "How to know the unix version"
date: "2017-04-03 10:00:00 -0200"
author:
    name: "Marcel Nakamine"
    url: "https://www.blogger.com/profile/15113696834989107891?rel=author"
    image: "//lh3.googleusercontent.com/zFdxGE77vvD2w5xHy6jkVuElKv-U9_9qLkRYK8OnbDeJPtjSZ82UPq5w6hJ-SA=w35"
categories: [unix]
---

Para saber sobre o kernel:
```
uname -a
```

Exemplo de saída:

```
Linux 4.13.0-37-generic #42~16.04.1-Ubuntu SMP Wed Mar 7 16:03:28 UTC 2018 x86_64 x86_64 x86_64 GNU/Linux
```

E sobre a distro de Linux:
```
cat /etc/*{release,version}
```

Exemplo de saída:

```
DISTRIB_ID=Ubuntu DISTRIB_RELEASE=16.04 DISTRIB_CODENAME=xenial DISTRIB_DESCRIPTION="Ubuntu 16.04.4 LTS" NAME="Ubuntu" VERSION="16.04.4 LTS (Xenial Xerus)" ID=ubuntu ID_LIKE=debian PRETTY_NAME="Ubuntu 16.04.4 LTS" VERSION_ID="16.04" HOME_URL="http://www.ubuntu.com/" SUPPORT_URL="http://help.ubuntu.com/" BUG_REPORT_URL="http://bugs.launchpad.net/ubuntu/" VERSION_CODENAME=xenial UBUNTU_CODENAME=xenial
```

Fontes:

https://superuser.com/

