# Como matar a tu viejo Django y dejar crecer a sus hijitos
Desde OpenExO hemos estado trabajando durante varios años en nuestra plataforma monolítica basada en Django. 
Hace un año vimos que la situación era insostenible y decidimos cambiar a un enfoque de microservicios, basados en Django y dando continuidad al negocio.
Nos gustaría compartir nuestra experiencia a día de hoy en este camino.

## Formato de la propuesta

Indicar uno de estos:

* Charla (50 minutos)

## Descripción

No es una charla más sobre teoría de microservicios, es una reflexión real de como estamos migrando una plataforma monolítica en Django hacia un enfoque de servicios basados en Django.

Veremos como con esta arquitectura se pueden afrontar problemas reales de las startups y como nos permite prepararnos para escalar nuestro negocio. Hablaremos de conceptos como la dockerización, el despliegue de la aplicación, la gestión del código entre desarrolladores, entornos de tests, así como la autenticación, comunicación entre servicios, etc.

Todo esto recogido desde nuestra experiencia, con lecciones aprendidas, con fallos y feedback de otras partes de la empresa. Uno de los principales handicaps de este enfoque es como hacerlo a la misma vez que el negocio continua evolucionando y se tiene que dar soporte a los usuarios actuales.

La base tecnológica es el software libre, ya que nuestro framework principal es Django, y hacemos uso de otras plataformas de software libre como Lightbus o SocketShark para la comunicación entre servicios. Ademas, en nuestro repositorio de GitHub puedes encontrar diversos paquetes que hemos ido liberando y que pueden ser reutilizados a través de PyPI (la mayor parte de ellos son apps para Django).

## Público objetivo
Desarrolladores que se interesen por la arquitectura de las aplicaciones.

## Ponente(s)

Tomas Garzon, desarrollador backend en Django desde 2006, cofundador de IActive Intelligent Solutions y actualmente Lead Software Developer en OpenExo. Ponente en PyCon 2016 en Almeria.
