Instrucciones para actualizar la página y que el menú esté en inglés cuando se selecciona el inglés:
1. Hacer todas las actualizaciones necesarias (proyectos, noticias, miembros del grupo, etc.).
2. En _site cambiar manualmente, a nivel de HTML, el menú superior en todas las páginas que estén en inglés. Basta con reemplazar el código que está entre las líneas especificadas aquí entre corchetes, que es el que especifica el menú superior de cada página, con el código que puedes encontrar justo aquí abajo. Los archivos a modificar son:
    * _site/en/index.html, líneas [94, 142]
    * _site/en/what-we-do/index.html, líneas [92, 140]
    * _site/en/projects/index.html, líneas [92, 140]
    * _site/en/members/index.html, líneas [92, 140]
    * _site/en/media/index.html, líneas [92, 140]
    * _site/en/contact/index.html, líneas [92, 140]
3. ¡Ya está! Commit y push origin y deberías poder verlo en https://futbol-y-redes.github.io

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
