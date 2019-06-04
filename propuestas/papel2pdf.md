# Emulando impresoras para generar PDF

El flujo de trabajo de mi unidad depende de una aplicación legacy (IBM, 
terminales 3270, impresoras 3287) y como conseguí que se generasen en 
lugar de papel. 

## Formato de la propuesta

* Charla (50 minutos)

## Descripción

Primero explicaré cómo se gestó el sistema de impresión actual en los 80 con impresoras XEROX, narraré una pequeña crisis que nos ocurrió a mediados de los 90 que fue crucial para la solución actual.

Después explicaré el flujo de trabajo "clásico" con la aplicación y por último mostraré la solución actual con streams de impresión anonimizados sobre un hardware similar al que uso en el trabajo.

La solución actual:

* Hardware:
  + Raspberry Pi 3B+
    
* Software:
  + Raspbian (Debian based)
  + DateTime (https://metacpan.org/pod/DateTime#COPYRIGHT-AND-LICENSE) The Artistic License 2.0
  + x3270 (http://x3270.bgp.nu/) BSD/MIT
  + GhostPCL (https://ghostscript.com/GhostPCL.html) Affero GPL

## Público objetivo

La charla esta pensada para que sea accesible al publico no técnico. Esta mas 
centrada en conceptos que en las herramientas utilizadas, tiene alguna parte de 
gestión de sistemas y Perl. 


## Ponente(s)

José Luis Perez Diez.
Barcelona Perl mongers.
Actualmente fuera de IT en la Generalitat de Catalunya, anteriormente
programador, administrador de sistemas y soporte de segundo nivel.
Granada Perl Workshop, Granada love 4 Perl, Cluj YAPC, y en muchos de 
los eventos organizados por Barcelona Perl mongers.

