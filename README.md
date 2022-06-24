<div align="center">

  <img src="https://raw.githubusercontent.com/devschile/media-press/master/devschile2018-growler.png" alt="logo" width="200" height="auto" />
  <h1>DevsChile('Persa')</h1>
  
  <p>VENDE y COMPRA dentro de la comunidad.</p>

</div>

## :camera: Screenshots

<div align="center"> 
  <img src="https://i.imgur.com/VdrmcoO.png" alt="screenshot" />
</div>

## :space_invader: Tech Stack

- [Hugo v0.9](https://gohugo.io/)

<!-- Getting Started -->
## 	:toolbox: Cómo publicar

Crea tu publicación en el directorio `/cachureos/vendo_<producto>.md`. Los parámetros del `head` del documento _markdown_ son:

```bash
+++
date = 2022-06-16T10:00:00Z           # requerido, esta fecha se va a publicar tu aviso
title = "Vendo ...."                  # requerido
precio = "$666.666"                   # requerido, opcional poner si es CLP, USD u otra moneda
vigente = true                        # requerido, booleano si se vende cambiar a false
negociable = false                    # opcional, booleano si el precio es conversable
lugar = "Región Metropolitana"        # opcional, si lo que vendes tienen que juntarse a entregarlo es importante
tags = ["macbook pro", "usado"]       # opcional, string con etiquetas para que tu aviso se encuentre mejor
categories = "Vendo"                  # requerido, string "Vendo" o "Compro"
fotos = []                            # opcional, array de url's de las fotos

[contacto]                            # requerido
  slack = "@huemul"                   # requerido, nick del slack para que te ubiquen
  nombre = "Huemul da Silva"          # opcional
  email = "huemul@devschile.cl"       # opcional
  celular = "+56911111111"            # opcional
+++

<!-- DESCRIPCION COMPLETA DE TU AVISO -->
...
```

## :wave: Cómo contribuir

- Revisa los [issues](https://github.com/devschile/persa/issues).
- Únete al team _Huemul Devs_ en [Slack DevsChile](https://devschile.cl/) canal `#huemul-devs` y colabora con nosotros en esta y otras iniciativas.

## :warning: License

Distributed under the no License.
