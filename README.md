# Valdimir's Blog

- Vladimir Remar isx48262276
- Data: 14 Abril 2018
- Adm. Sistemes informatics en xarxa
- Modul Professional 9: Implantacio d'aplicacions web
---

## Proposito General

Mostrar los conocimientos adquiridos durante el curso para gestionar una
pagina web estatica, tanto su contenido como su propia estructuracion.

---

## Pagina Web
- Home: Con un mensaje de bienvenida.
- About: Tema a tratar.
- Blog: Un blog con diferentes entradas.
- Tags: Tags utilizados.

---

## Tratamiento de la pagina web

- Para el tratamiento de la pagina web me base en un tema de Jekyll
[Jekyll-uno](https://github.com/joshgerdes/jekyll-uno).
- Gestion "visual" dispuse de mi propio [css](/css/main.css).
- Tags emplee un pequeño [script](/js/main.js) en java-script el cual me 
ayudo en la gestion de los mismos.
- Implementacion de [DISQUS](/_includes/disqus.html)
- El resto es emplear el propio lenguaje HTML.

---

## Uso de Jekyll

Utilice Jekyll porque es un gestor muy versatil el cual facilita la 
estructuracion de la pagina web y te permite tener orden con los elementos
que la rodean.

Instalacion y test local:

    sudo dnf install rubygems rubygems-devel ruby-devel
    sudo dnf install redhat-rpm-config
    # finalment
    gem install jekyll bundler
    jekyll new my-awesome-site
    cd my-awesome-site
    bundle exec jekyll serve

    # => Now browse to http://localhost:4000

Asi entonces podemos ver en funcionamiento Jekyll y la estructura de
directorios que genera.

### Jekyll en nuestra web

Estructura de direcorios:

    ├── about
    │   └── index.html
    ├── blog
    │   └── index.html
    ├── _config.yml
    ├── css
    │   └── main.css
    ├── fonts
    │   └── foundation-icons
    │       ├── foundation-icons.eot
    │       ├── foundation-icons.svg
    │       ├── foundation-icons.ttf
    │       └── foundation-icons.woff
    ├── images
    │   ├── bass_players.jpg
    │   ├── bp_jaco.jpg
    │   ├── bp_james.jpg
    │   ├── cover.jpg
    │   ├── cycling.jpg
    │   ├── profile.jpg
    │   └── victor.jpg
    ├── _includes
    │   └── footer.html
    ├── index.html
    ├── js
    │   └── main.js
    ├── _layouts
    │   ├── about.html
    │   ├── categories.html
    │   ├── default.html
    │   ├── page.html
    │   ├── post.html
    │   └── tags.html
    ├── _posts
    │   ├── 2014-04-30-hank-quinlan-site-launched.md
    │   ├── 2016-05-13-cyling.md
    │   └── 2017-11-30-bass-players.md
    ├── README.md
    ├── _sass
    │   └── icon.scss

---

## Features

* Clean layout
* Resposive layout
* Syntax highlighting
* Social links
* Tags listing page
* Disqus integration

