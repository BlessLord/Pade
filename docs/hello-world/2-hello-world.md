---
layout: post
title: Hello World
image: '/assets/img/'
description: Inicializando a plataforma PADE
categories: docs
permalink: /docs/hello-world/
---

PADE foi implementado com um objetivo central: simplicidade!

Depois de ter o PADE instalado em seu computador fica bem simples começar a trabalhar.

Em uma pasta crie um arquivo chamado start_ams.py com o seu editor de texto preferido, e copie e cole o seguinte trecho de código dentro dele:

```python
# este e o arquivo start_ams.py
from pade.misc.common import set_ams, start_loop

if __name__ == '__main__':
    set_ams('localhost', 8000)
    start_loop(list(), gui=True)
```

A essa altura você já deve estar vendo a interface gráfica de monitoramento dos agentes em Python, assim como essa:

![Pade Interface]({{ site.baseurl }}/img/InterfaceSniffer.png)
