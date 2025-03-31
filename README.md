**Instrucciones para actualizar la página**

Existen dos formas. La primera es la más sencilla y la que recomiendo para pequeños cambios o adiciones, la segunda es más recomendable si se quiere modificar algo sustancial de la web. Si quisiera añadir un nuevo miembro, o modificar una foto, una descripción o parte de un texto, utilizaría el primer método, por ejemplo. 

a)	Cambiar directamente el HTML del sitio. Ya está, no hay más truco.

b)	Volver a generar la web y modificarla al generarla con Jekyll. Para ello:
1.	Clonar el repositorio y descomprimir el archivo futbol-y-redes.github.io_completa.zip.
2.	Instalar Jekyll (https://jekyllrb.com/docs/) y todos sus prerrequisitos siguiendo las instrucciones del link.
3.	Ejecutar “bundle exec jekyll serve” para generar la web en local. Hacer todos los cambios necesarios. 
4.	La ventaja de Jekyll y Minimal Mistakes (el tema usado) es que el sitio se puede desarrollar en Markdown, sin necesidad de modificar HTML. La desventaja es que no da soporte a sitios multilingües; las páginas en distintos idiomas se generan igual, pero luego no hay forma de hacer que el menú principal cambie de idioma y redireccione a las páginas adecuadas. Para solventar esto y lograr que la web esté en inglés y español, hacer Ctrl + C para dejar de correr la web en local.
5.	**Sin Jekyll ejecutándose** (de lo contrario, todos los cambios que hagas serán sobreescritos desde la plantilla del Markdown por Jekyll), copiar y pegar los contenidos del directorio "_site" en el repositorio. Solo ese directorio contiene la web completa en HTML, con todo lo necesario para que funcione de forma autónoma. Así, estamos logrando que la web que hemos visualizado en local sea la que está subida a GitHub.
6. En _site cambiar manualmente, a nivel de HTML, el menú superior en todas las páginas que estén en inglés. Basta con reemplazar el código que está entre las líneas especificadas aquí entre corchetes, que es el que especifica el menú superior de cada página, con el código que puedes encontrar justo aquí abajo. Los archivos a modificar son:
    * _site/en/index.html, líneas [94, 142]
    * _site/en/what-we-do/index.html, líneas [92, 140]
    * _site/en/projects/index.html, líneas [92, 140]
    * _site/en/members/index.html, líneas [92, 140]
    * _site/en/media/index.html, líneas [92, 140]
    * _site/en/contact/index.html, líneas [92, 140]
7. Comprime la web con las modificaciones y sustitúyela por futbol-y-redes.github.io_completa.zip para futuros cambios.
8. ¡Ya está! Commit y push origin y deberías poder verlo en https://futbol-y-redes.github.io

<div class="masthead">
  <div class="masthead__inner-wrap">
    <div class="masthead__menu">
      <nav id="site-nav" class="greedy-nav">
        
          <a class="site-logo" href="/"><img src="/assets/images/logo.jpeg" alt="FutbolyRedes"></a>
        
        <a class="site-title" href="/">
          FutbolyRedes
          
        </a>
        <ul class="visible-links">
<li class="masthead__menu-item">
              <a href="/en/what-we-do/" title="Get to know what we do.">What we do</a>
            </li>
<li class="masthead__menu-item">
              <a href="/en/projects/" title="Learn about our projects.">Projects</a>
            </li>
<li class="masthead__menu-item">
              <a href="/en/media/" title="Read what the media say about us.">Media</a>
            </li>
<li class="masthead__menu-item">
              <a href="/en/members/" title="Meet our current and past members.">Members</a>
            </li>
<li class="masthead__menu-item">
              <a href="/en/contact/" title="Contact us.">Contact</a>
            </li>
<li class="masthead__menu-item">
              <a href="/en/" title="Switch to English."><img class="emoji" title=":uk:" alt=":uk:" src="https://github.githubassets.com/images/icons/emoji/unicode/1f1ec-1f1e7.png" height="20" width="20"></a>
            </li>
<li class="masthead__menu-item">
              <a href="/" title="Cambia a español."><img class="emoji" title=":es:" alt=":es:" src="https://github.githubassets.com/images/icons/emoji/unicode/1f1ea-1f1f8.png" height="20" width="20"></a>
            </li>
</ul>
        
        <button class="search__toggle" type="button">
          <span class="visually-hidden">Toggle search</span>
          <i class="fas fa-search"></i>
        </button>
        
        <button class="greedy-nav__toggle hidden" type="button">
          <span class="visually-hidden">Toggle menu</span>
          <div class="navicon"></div>
        </button>
        <ul class="hidden-links hidden"></ul>
      </nav>
    </div>
  </div>
</div>
