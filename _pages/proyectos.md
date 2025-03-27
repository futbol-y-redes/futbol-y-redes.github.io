---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: "Proyectos"
ref: proyectos
lang: es

intro_proyectos:
  - excerpt: "Si tiene que ver con Redes y Fútbol, allí estaremos. Desde identificar el juego de un equipo hasta medir la entropía que se genera durante un partido. Si lo lees aquí, es que ya forma parte del pasado. Para saber qué es lo que tenemos justo ahora entre manos... ¡Contacta con nosotros!"

feature_row_1:
  - image_path: assets/images/pic04.jpg
    alt: "Identificabilidad de un equipo"
    title: "Identificabilidad de un equipo"
    excerpt: "Identificar patrones en el juego de un equipo, o en el de un rival, puede ayudar a maximizar el rendimiento colectivo. En colaboración con LaLiga, hemos analizado las matrices de pases de todos los equipos de primera división para cuantificar qué equipos tienen un patron más definido. Utilizando las métricas de identificabilidad, mostramos como es posible detectar qué equipos impusieron su estilo en un partido, independientemente del resultado."
    url: "https://www.agenciasinc.es/Noticias/Ciencia-de-redes-para-analizar-como-juegan-los-equipos-de-futbol"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: /assets/images/pic05.jpg
    alt: "La paradoja de los pases por gol"
    title: "La paradoja de los pases por gol"
    excerpt: "¿Más pases es sinónimo de más goles? En este análisis observamos cómo, a pesar de que los equipos que realizan más pases suelen acabar en las posiciones más altas de la tabla, existe un factor fundamental en la relación entre pases y goles: el momento del partido en que nos encontremos. Y es que en las segundas partes hay menos pases... ¡pero más goles!"
    url: "https://www.marca.com/futbol/laboratorio-datos/2020/05/26/5ec8cc9de2704ee13b8b4628.html"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: assets/images/pic06.jpg
    alt: "Las Redes (Complejas) de Guardiola"
    title: "Las Redes (Complejas) de Guardiola"
    excerpt: "En el año 2009, un Barcelona bajo el mando de Pep Guardiola, consigo ganar las seis competiciones en las que participó. Y no solo eso. Su estilo de juego marcó un antes y un después en la historia del fútbol. En este trabajo, analizamos la estructura de las redes de pases del Barça de Guardiola, mostrando en qué era diferente del resto de equipos de LaLiga. Este trabajo fue escogido como uno de los más relevantes del año 2019 por la revista Scientific Reports."
    url: "https://www.nature.com/articles/s41598-019-49969-2"
    btn_label: "Leer más"
    btn_class: "btn--primary"
feature_row_2:
  - image_path: /assets/images/pic07.jpg
    alt: "¿Por qué son útiles las redes en el fútbol?"
    title: "¿Por qué son útiles las redes en el fútbol?"
    excerpt: "Gracias a la Ciencia de las Redes se puede cuantificar cómo es de importante un jugador para todo el equipo, pero también la alineación de un grupo específico de jugadores. Se pueden evaluar (y predecir) los efectos que tendría la sustitución de un jugador, o incluso plantear un partido en función de la red de pases del equipo contrario. Y todo ello simplemente llevando las matemáticas al fútbol."
    url: "https://doi.org/10.3389/fpsyg.2018.01900"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: assets/images/pic08.jpg
    alt: "Entropía en el fútbol"
    title: "Entropía en el fútbol"
    excerpt: "La entropía de un sistema está relacionada con la cantidad de desorden que hay en el mismo, pero también con cómo de aleatorio es su comportamiento. Partiendo de esta base, es posible evaluar el desorden espacial de los equipos de fútbol y cómo su organización va variando a lo largo del partido. Curiosamente, los equipos tienen algunas propiedades que fluctúan de manera muy aleatoria, pero otras no tanto..."
    url: "https://www.mdpi.com/1099-4300/22/2/172"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: /assets/images/pic09.jpg
    alt: "Redes de Campo & F.C. Barcelona"
    title: "Redes de Campo & F.C. Barcelona"
    excerpt: "Las redes de pases no tienen que ser necesariamente entre jugadores. También se pueden construir redes de campo, donde es posible estudiar las propiedades espaciales de los pases (dónde se pasa más, de dónde a dónde, ...). Este tipo de redes permite descirbir el juego de un equipo yendo más allá de los jugadores. Un ejemplo práctico, es este estudio sobre el juego del Barça de Guardiola."
    url: "https://www.sciencedirect.com/science/article/pii/S0960077920303337"
    btn_label: "Leer más"
    btn_class: "btn--primary"

permalink: /proyectos/
---

# Proyectos

{% include feature_row id="intro_proyectos" type="center" %}

{% include feature_row id="feature_row_1"  %}

{% include feature_row id="feature_row_2"  %}



