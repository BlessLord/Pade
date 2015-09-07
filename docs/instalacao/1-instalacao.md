---
layout: post
title: Instalação
image: '/assets/img/'
description: Como instalar o PADE no seu computador utilizando o terminal e o comando pip install
categories: docs
permalink: /docs/instalacao/
---

Instalar o PADE em seu computador, ou dispositivo embarcado é bem simples, basta que ele esteja conectado à internet, então basta digitar em um terminal:

```bash
$ pip install pade
```

Pronto! O Pade está instalado!

Se você quiser ter acesso ao fonte do PADE e instala-lo a partir do fonte, basta digitar as seguintes linhas no terminal:

```bash
$ git clone https://github.com/lucassm/Pade
$ cd Pade
$ python setup.py install 
```

Pronto o PADE está pronto para ser utilizado, faça um teste no IPython digitando:

```python
from pade.misc.utility import display_message
```
