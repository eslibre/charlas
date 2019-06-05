# Palomitas: torrent streaming

Herramientas de software libre para trabajar con torrents en la web.
Reproducción de video antes de completar la descarga con tecnologías de streaming y estadísticas en tiempo real a través de websocket.

## Formato de la propuesta

Indicar uno de estos:

* Charla (50 minutos) (quizá un poco menos)

## Descripción

La idea de esta charla es presentar las herramientas que tenemos para trabajar con torrents en la web, a través de los componentes de un sistema que un servidor lleva varios años desarrolando para consumir el contenido de forma cómoda en cualquier dispositivo con un navegador de internet.

Lo he llamado Palomitas en honor a Popcorn-Time y mi objetivo es conseguir una experiencia similar y explicar como podemos construir un producto similar solo con tecnologias web de software libre. Entre ellas están el streaming de video usando reproductores web de HTML5 con los elementos `<video>` y un servidor de streaming creado con Node.js y FFMPEG. Esto, junto con una conexión websocket que enviá estadísticas de las descargas y los peers / seeds y un panel de control responsive que muestra estas estadísticas nos da todo lo necesario para la reproducción de torrents en la web

[palomitas-dl](https://github.com/juandjara/palomitas-dl) es el núcleo de la aplicación, contiene la API REST para la gestión de torrents y el panel del control.

[sub-down](https://github.com/juandjara/sub-down) es un servicio que sirve para buscar subtitulos en `openSubtitles`, ya sea por una cadena de texto simple o con el identificador de IMDB. También convierte los subtitulos a un formato usable para los navegadores.

[palomitas](https://github.com/juandjara/palomitas) es el cliente más completo, el front-end principal, y el que tiene el mejor catálogo. Se apoya en una API de Popcorn Time y los dos servicios mencionados anteriormente para construir la interfaz de visualización de los videos, te recuerda las series que has visto y tiene un diseño muy amigable.

Y por último esta dibujitos [dibujitos](https://github.com/juandjara/dibujitos) que es una idea similar para otro front-end pero con un catálogo de anime de la web nyaa.si y metadatos de kitsu combinados en [otra API](https://github.com/juandjara/dibujitos-api) que se encarga de cachear las consultas.

## Público objetivo

Esta charla va dirigida a gente que tenga nociones de programación web y le interese el mundo de los torrents

## Ponente(s)

* Juan Domínguez Jara, Front-end engineer @ Geographica (CARTO).
* He dado un par de charlas en la ETSII de Sevilla cuando estudiaba Ingeniera del Software allí.

