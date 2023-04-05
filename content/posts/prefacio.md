---
title: "Prefacio"
summary: 'Planisferio de la web: pasado y presente'
date: 2003-03-31T01:36:50+02:00
---

# Una historia.

Estoy sentado. No estoy haciendo nada fundamentalmente distinto de lo que haría hace un cuarto de siglo. Estoy escribiendo estas líneas. Navego insertando enlaces en el navegador que me toque, hoy Vivaldi, uno de tantos sabores del motor Blink. Lo elijo particularmente por detalles como poder tomar notas al vuelo o capturar páginas web. Giro la silla y veo el cielo, pensando en esta maravilla que nos hemos dado. Tomamos como cotidiano el exponer un trozo de información cualquiera al mundo, sea un texto, una imagen o un vídeo, así como enlazar otros trocitos, pero no fue siempre así.



La idea de un sistema de hipertexto como tal, enlazando trocitos de información, resumidos en páginas, de tal forma que formen una telaraña o _web_ es relativamente reciente. Memex, de Vannevar Bush en 1945, es el predecesor. En [_As We May Think_](https://web.archive.org/web/20011215033047/http://www.isg.sfu.ca/~duchier/misc/vbush/vbush-all.shtml) se exponía la idea. Bush observa que la forma en la que se comunicaban los descubrimientos científicos llevaba ya generaciones y tenía síntomas de aniquilosamiento, cada vez más información, más difícil de encontrar.

## El pasado

Hará veinte años, un navegador mandaba sobre todos los demás por antonomasia, Internet Explorer, luego Netscape y por último menos conocidos como Konqueror, Mozilla, Galeon u Opera. Abundaban los editores WYSIWYG (*What you see is what your get*) para hacerte tu propia página web de manera visual, empezando por [Netscape Composer](http://recursostic.educacion.es/observatorio/web/es/software/software-general/86-composer-70-un-sencillo-editor-web-gratuito), Frontpage o [Dreamweaver](http://roble.pntic.mec.es/apuente/dw_4_ini/siete.htm), que era lo más completo dentro de esta categoría. Se podía hacer tu web picando, y se hacía, pero muchos optaban por crear su página web como si de un documento Word se tratase, por las numerosas incompatibilidades que había. Que si algo funcionaba sólo en IE, que si una página que cumpliese con los estándares de W3C se veía descuadrada y que si patatín.

En cuanto a la navegación, tenía de primeras Google. Y a poco de asomarse, [podía encontrarse con directorios](https://web.archive.org/web/20051025205031/http://www.anime100.com/rules.shtml). Podía [hallarse con páginas individuales que recopilaban algunos enlaces interesantes](http://sauce.pntic.mec.es/\~jarce/Web_Recursos/musicotr.htm). Hoy queda el recuerdo, queda el retrofuturismo, como en [The Old Net](https://theoldnet.com), otra interfaz para llevarte a cómo eran las webs en el pasado. La simulación es creíble, desgraciadamente, detalles como según qué imágenes o las funcionalidades de las webs dinámicas se pierden. También ciertas prácticas de software no estaban tan extendidas y faltaba bastante automatización. No era raro copiar partes del diseño a cada página que se hiciese.

Hoy, en estos renglones, nos extenderemos en cómo ser soberano en la Web, en cómo tener tu propio espacio. Empezaremos por nociones básicas de redes y computación para seguir con HTML.

# Web hodierna

Éste es un sitio web para que el respetable pergeñe su espacio en Internet. Iba a ser una serie de artículos en [mi bitácora](http://robledo.prose.sh), pero la variedad de conocimientos a transmitir, el alcance y poner las notas sueltas que tengo en algo coherente implica un trabajo de mayores dimensiones, acabando por ser una página propia en [Hugo](https://gohugo.io).

## ¿Cómo arrancar un proyecto?

Los proyectos empiezan con un puñado de comandos, advirtiendo que previamente hemos de tener nuestra clave SSH, [muy bien explicado en este curso de The Odin Project](https://www.theodinproject.com/paths/foundations/courses/foundations#git-basics):

```bash
cd ~/www
git clone git@github.com:[usuario]/[repositorio].git
cd [repositorio]
code .
```

Antes de ello, debemos haber creado nuestro repositorio en Github, sea de este estilo: `https://github.com/[usuario]/[repositorio].git`. Nos vamos a remontar aún más atrás. ¿Para qué sirve Git? Sencillamente, es un sistema de control de versiones. ¿Y para qué nos vendrá bien? Imaginemos que tenemos que empezar un proyecto, sea esta página web o una enciclopedia y no queremos volver a incurrir en prácticas como archivos denominados «Trabajo nuevo 1.txt» o que se pierda todo si la pifiamos. Trabajaremos con texto plano (¡esto es importante, ya que permitirá trazar mejor los cambios!). No estaremos trabajando con ficheros Word, que en nuestro editor se verán así:

![](/assets/garbled_docx.png)

¿Dónde se aloja esta página, como la de ejemplo? Neocities, sucesor espiritual de Geocities, es un servicio de alojamiento web, además de ser una red sovial primigenia, en donde crear fácilmente tu espacio en la web. [Ejemplos](https://districts.neocities.org) abundan, fuentes de inspiración.

# ¿Qué necesito?

* Un editor de texto plano. Muchos usaréis Windows, en este caso [Notepad++](https://notepad-plus-plus.org/downloads/) es muy bueno

Así, manos a la obra, tenemos este índice para que veáis lo que nos espera.

0. **Prefacio. Planisferio de la web: pasado y presente.**

1.  Comparte tus pensares, pareceres y pesares, sé soberano. ¿Por qué renunciar a los oligopolios?

2.  Planificando tu web

3.  HTML como si estuvieses en 1993

4. Markdown/Pandoc

    4.1 CSS básico

5.  HTML moderno

6.  CSS a fondo

    6.1 Flexbox

    6.2 Grid

7.  Diseño web práctico

    7.1 Interfaces.

    7.2 Exposición de por qué usar tus propios diseños.

    7.3 Cuando hay que usar frameworks propios.

8.  Sitios estáticos

9.  CI/CD: despliegue de tus obras.

10.  Plvs vltra, dónde aprender más cosas de la web y propuesta de proyecto final
