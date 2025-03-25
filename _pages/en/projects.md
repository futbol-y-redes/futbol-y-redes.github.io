---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
title: "Projects"
ref: proyectos
lang: en

intro_proyectos:
  - excerpt: "If it has to do with Networks and Soccer, we will be there. From identifying a team's style of playing, to measuring the entropy generated during a match. Whatever you read here is already part of the past. To find out what we have right now, just contact us!"

feature_row_1:
  - image_path: assets/images/pic04.jpg
    alt: "Identifiability of a team"
    title: "Identifiability of a team"
    excerpt: "Identifying patterns in a team's game, or in that of an opponent, can help maximize collective performance. In collaboration with LaLiga, we have analyzed the passing matrices of all the first division teams to quantify which teams have a more defined pattern. Using the identifiability metrics, we show how it is possible to detect what teams imposed their style in a match, regardless of the result."
    url: "https://newsletter.laliga.es/futbol-global/analisis-de-los-expertos-en-futbol-de-los-equipos-de-laliga"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/images/pic05.jpg
    alt: "The pass-goal paradox"
    title: "The pass-goal paradox"
    excerpt: "Do more passes lead to more goals? In this analysis, we observe how, despite the fact that the teams that make the most passes tend to finish in the highest positions in the table, there is a fundamental factor in the relationship between passes and goals: The moment of the match we are in. Interestingly, it is at the second halves of matches when fewer passes are made ... but more goals! are scored!"
    url: "https://www.marca.com/futbol/laboratorio-datos/2020/05/26/5ec8cc9de2704ee13b8b4628.html"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: assets/images/pic06.jpg
    alt: "Guardiola's (Complex) Networks"
    title: "Guardiola's (Complex) Networks"
    excerpt: "In 2009, a Barcelona under the command of Pep Guardiola, managed to win the six competitions in which they participated. Not only that. Guardiola's style of playing was a milestone in the history of football. In this work, we analyze the structure of Guardiola's Barça passing networks, showing how it was different from the other LaLiga teams. This work was chosen as one of the most relevant of the year 2019 by Scientific Reports journal."
    url: "https://www.nature.com/articles/s41598-019-49969-2"
    btn_label: "Read more"
    btn_class: "btn--primary"
feature_row_2:
  - image_path: /assets/images/pic07.jpg
    alt: "Why Are Networks Useful In Soccer?"
    title: "Why Are Networks Useful In Soccer?"
    excerpt: "Thanks to Network Science it is possible to quantify how important a player is for the entire team, but also the alignment of a specific group of players. We can evaluate (and predict) the effects that a player's substitution would have, or even prepare a match based on the opposing team's passing network. And all of that just by applying mathematics to football..."
    url: "https://doi.org/10.3389/fpsyg.2018.01900"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: assets/images/pic08.jpg
    alt: "Entropy In Soccer"
    title: "Entropy In Soccer"
    excerpt: "The entropy of a system is related to the amount of disorder the system has, but also to how random its behavior is. Starting from this framework, it is possible to evaluate the spatial disorder of the soccer teams and how their organization varies throughout the match. Interestingly, teams have some properties that fluctuate very randomly, while others seem more predictable..."
    url: "https://www.mdpi.com/1099-4300/22/2/172"
    btn_label: "Read more"
    btn_class: "btn--primary"
  - image_path: /assets/images/pic09.jpg
    alt: "Pitch Networks & F.C. Barcelona"
    title: "Pitch Networks & F.C. Barcelona"
    excerpt: "Passing networks do not necessarily connect players. Pitch networks can also be constructed, leading to the study of the spatial properties of passing patterns. This type of networks allows to interpret the game of a team going beyond players. You can find a practical example in the study we carried out about Guardiola's Barça and its organization."
    url: "https://www.sciencedirect.com/science/article/pii/S0960077920303337"
    btn_label: "Read more"
    btn_class: "btn--primary"

permalink: /en/projects/
---

# Projects

{% include feature_row id="intro_proyectos" type="center" %}

{% include feature_row id="feature_row_1"  %}

{% include feature_row id="feature_row_2"  %}



