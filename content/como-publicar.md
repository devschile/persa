+++
title = "¿Y kómo publiko akí?"
layout = "page"
+++
**¡Muy fácil!** Si eres fronén tienes ya la mitad del trabajo hecho, si eres bakén te va a costar un poco más:

1. Forkea y clona el [repositorio de GitHub](https://github.com/devschile/persa).
2. Crea tu publicación en el directorio `/cachureos/vendo_<producto>.md`. Los parámetros del `head` del documento _markdown_ son:
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

3. Si quieres probar tu posteo:
    1. Debes instalar [Hugo](https://gohugo.io/) y correr el comando `$ hugo server` para previsualizar en tu `http://localhost:1313/`.
4. Envía tu posteo:
    1. _commit, push_ y haz un _pull request_ sin olvidar verificar lo que estás agregando.
    2. Agrega como reviewers a `@leonardo`, `@hector`, `@gmq` y/o `@jorgeepunan`.
    3. Coméntalo en Slack canal [#comunidad](http://devschile.slack.com/messages/comunidad) y será revisado, testeado, linteado y si pasa los rigurosos análisis de la _Intelijencia Artifisial_, será publicado.
