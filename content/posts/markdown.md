---
title: "4. Markdown y Pandoc"
summary: 'Exprésate y llévate tus palabras fácilmente'
date: 2006-03-31T01:36:50+02:00
---

Como vimos en [la entrega anterior](html) con un viaje completo por HTML, Markdown es otro lenguaje de marcado, [ideado en 2004](https://daringfireball.net/projects/markdown/) por Gruber y Schwarz. Desde su fundación tuvo el propósito de ser un lenguaje sencillo y bastante intuitivo para quien escribiese con el fin de ser transformado rápidamente a HTML. Era una alternativa a otros lenguajes de marcado que se veían en aquel entonces, como [BBCode](https://en.wikipedia.org/wiki/BBCode), omnipresente en foros web y que incluía etiquetas como `[quote]cita[/quote]`. Para hacernos una idea, expondremos tres textos expresados con HTML, Markdown y BBCode respectivamente:

## HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Texto</title>
</head>
<body>
    <h1>Presentación</h1>
    <p>¡Bienvenidos a <strong>MiCiudad</strong>, un servicio web para expresarte! Te inscribes en una <em>ciudad virtual</em> y compartes lo que pienses, además de conocer a otros internaut@s como tú.</p>
</body>
</html>
```

## BBCode

```html
[style size="30px"]Presentación[/style]

¡Bienvenidos a [b]MiCiudad[/b], un servicio web para expresarte! Te inscribes en una [i]ciudad virtual[/i] y compartes lo que pienses, además de conocer a otros internaut@s como tú.
```

## Markdown

```md
# Presentación

¡Bienvenidos a **MiCiudad**, un servicio web para expresarte! Te inscribes en una _ciudad virtual_ y compartes lo que pienses, además de conocer a otros internaut@s como tú.
```

¿Se hacen una idea? Es muy fácil empezar a escribir algo en Markdown. Sólo unos pocos marcadores que aprenderemos en unos minutos y acabaremos recordando casi todos con unos pocos artículos escritos. Hay variaciones según el dialecto de Markdown, sea Telegram, Pandoc o Github, pero en general el lenguaje es identificable, como el caso de SQL, que tiene una gran parte común. Uno empieza a pensar en un encabezado y he aquí una almohadilla a seis, según el nivel, equivalente a `<h1>` a `<h6>` en HTML.