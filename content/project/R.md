---
title: "Paquetes de R"
summary: "Porque, joder, R me pone"
tags: ["R"]
math: false
# Optional featured image (relative to `static/img/` folder).
image_preview: "Rlogo.png"
date: 2017-03-13
---


## fisabior

Ahora mismo estoy trabajando en un paquete para dar un marco de trabajo común al grupo en el que me incluyo. Aunque hay paquetes que tratan de hacer eso mismo (me viene a la cabeza `ProjectTemplate`), la verdad es que no se ajustaba exactamente a lo que estábamos buscando, así que nos animamos a crear un paquete con nuestras milongas. Puedes consultarlo a través de la cuenta institucional de [FISABIO en GitHub](https://github.com/fisabio/) y puedes copiar lo que te dé la real gana o usarlo como y para lo que quieras.


## Este sitio

¡Sí! Este sitio también está hecho directamente desde `R`, gracias al paquete `blogdown` y a [Hugo](https://gohugo.io/overview/introduction/). Para usarlo, primero deberías instalarlo a través del paquete `devtools` con la instrucción `devtools::install_github(rstudio/blogdown)`. Para crear un sitio que use el mismo tema, puedes usar el comando `blogdown::new_site(theme = "gcushen/hugo-academic")`.

Al igual que antes, si lo deseas puedes utilizar el material a tu voluntad, el cual está colgado en mi cuenta de [GitHub](https://github.com/carlosvergara/carlosvergara.github.io).
