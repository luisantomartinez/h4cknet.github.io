---
layout: post
author: Marcelo Vázquez
---

Hola, hoy vamos a estar resolviendo la máquina **Lame**, esta máquina engloba las siguientes fases:

* Reconocimiento
* Explotación
* Escalada de privilegios

Os comparto el siguiente script en Python, un espectáculo:

```python
#!/usr/bin/python3

import requests

r = requests.get("http://localhost:4000")
```
