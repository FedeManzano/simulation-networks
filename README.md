<p align="center" style="border-radius: 50px; overflow: hidden;">
  <img src="imagenes/portada/portada.png" style='height: 300px; width: 370px overflow: hidden;'/>
</p>

# :earth_americas: Redes Informáticas 

A través del ```Packet Tracer 8.2.2.0400``` se incluirán un conjuno de temas relacionados con la configuración de redes informáticas.

 
 ## :information_source: Recursos externos

- [CISCO Packet Tracer 8.2.2.0400](https://www.netacad.com/es/articles/news/download-cisco-packet-tracer)
- [Imagen de la portada](https://www.netacad.com/)
- [Plano E-Draw-Max](https://www.edrawmax.com/)

## :clipboard: Recorrido
- [Estructura](#estrctura)
- [0-Introducción](#introducción)
- [1-Lan](#1-lan)
- [2-Voip](#2-voip)
- [Autor](#autor)


## Estrctura

1. <b>Lan</b>
    * <i>lan-simple.pkt</i>
    * <i>lan-dos-vlans-dhcp.pkt</i>
    * <i>lan-dos-vlans-cruzadas.pkt</i>
2. <b>Voip</b>
    * <i>voip-comunicacion-lan.pkt</i>
    * <i>voip-conexion-serial.pkt</i>
    * <i>voip-dial-peer.pkt</i>
3. <b>Rutas-Estáticas</b>
    * <i>rs-ruta-default.pkt</i>
    * <i>rs-ruta-estática.pkt</i>
    * <i>rs-ruta-flotante.pkt</i>
4. <b>Redundancias</b>
    * <i>red-un-enlace-dos-capas.pkt</i>
    * <i>red-dos-enlaces-dos-capas.pkt</i>
    * <i>red-dos-enlaces-tres-capas.pkt</i>
5.  <b>Ethenchannel</b>
    * <i>eth-tres-enlaces.pkt</i>
6. <b>Capa Física</b>
    * <i>presupuesto</i>
        * <i>presupuesto.txt</i>
    * <i>fisica-sucursal.pkt</i>
    * <i>plano_fisico.eddx</i>
    * <i>plano-fisico.png</i>
15. <b>:green_book: [Documentación PDF](doc.pdf)</b>

## Introducción

Proyectos realizados en el simulador de redes de [CISCO](https://www.cisco.com/site/ar/es/index.html). A lo largo de este trabajo se verán temas relacionados con los conceptos más importantes de las redes de computadoras (Voip, rutas estáticas, rutas dinámicas, redundancias, switching, capas, etc).

## :arrow_right: 1-LAN

Para comenzar vamos a realizar ejemplos sencillos de como configurar redes de área local utilizando SWITCHES,  ROUTERS y algunos hosts conectados a los dispositivos antes mencionados. 
En el primer ejemplo vamos a ver de que forma realizar lo propuesto anteriormente a través de un SWITCH modelo 2960 y un ROUTER 4331 con la configuración estática de las IP de los hosts conectados. 
El objetivo es definir distintas VLAN y distribuirlas por los puertos de diferentes SWITCHES con las configuraciones pertinentes para que puedan comunicarse entre sí.

> Todos los ejemplos menos el primero van a utilizar la configuración dinámica de las direcciones IPv4 e IPv6, y generando esquemas de red con VLANs cruzadas a través de rutas estáticas para incrementar la dificultad de los ejercicios.


:green_book: [...MAS (doc.pdf)](/doc.pdf)

## :telephone: 2-Voip

En el siguiente apartado se van a llevar a cabo configuraciones relacionadas con la administración de la ```telefonía```, utilizando el protocolo que permite la comunicación a través de la <b>voz (Voip)</b>.
Los ejemplos seleccionados para este documento son tres, en los cuales se van a poner en práctica todos los conceptos relacionados con esta sección. Es importante tener en cuenta que existen dos tipos de redes:

- La primera es la que para la comunicación de dos o más hosts se utiliza un servidor como intermediario que permite dirigir los recursos compartidos a los destinos correctos <b>```(CLIENTE-SERVIDOR)```</b>.

- El otro tipo de red es la que no se necesita un servidor que administre la comunicación sino que los dispositivos que quieren compartir recursos lo hacen directamente uno con el otro sin necesidad de un intermediario, a este tipo de red se las denomina ```(PEER-TO-PEER)```.

:green_book: [...MAS (doc.pdf)](/doc.pdf)

## Autor
[Federico Manzano](http://github.com/FedeManzano)


