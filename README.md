<p align="center"
  style="border-radius: 50px; overflow: hidden;">
  <img src="imagenes/portada/portada.png" 
  style='height: 300px; width: 370px overflow: hidden;'/>
</p>

# Redes Informáticas 

A través del ```Packet Tracer 8.2.2.0400``` se incluirán un conjuno de temas relacionados con la configuración de redes informáticas.

## Recursos externos

- [CISCO Packet Tracer 8.2.2.0400](https://www.netacad.com/es/articles/news/download-cisco-packet-tracer)
- [Imagen de la portada](https://www.netacad.com/)



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
15. <b>[Documentación PDF](doc.pdf)</b>

## Recorrido
- [0-Introducción](#introducción)
- [1-Lan](#1-lan)
- [2-Voip](#2-voip)
- [Autor](#autor)

## Introducción

Proyectos realizados en el simulador de redes de [CISCO](https://www.cisco.com/site/ar/es/index.html). A lo largo de este trabajo se verán temas relacionados con los conceptos más importantes de las redes de computadoras (Voip, rutas estáticas, rutas dinámicas, redundancias, switching, capas, etc).

## 1-LAN

Para comenzar vamos a realizar ejemplos sencillos de como configurar redes de área local utilizando SWITCHES,  ROUTERS y algunos hosts conectados a los dispositivos antes mencionados. 
En el primer ejemplo vamos a ver de que forma realizar lo propuesto anteriormente a través de un SWITCH modelo 2960 y un ROUTER 4331 con la configuración estática de las IP de los hosts. 
El objetivo es definir distintas VLAN y distribuirlas por los puertos de diferentes SWITCHES con las configuraciones pertinentes para que puedan comunicarse entre sí.

> Todos los ejemplos menos el primero van a utilizar la configuración dinámica de las direcciones IPv4 e IPv6, y generando esquemas de red con VLANs cruzadas a través de rutas estáticas para incrementar la dificultad de los ejercicios.


[...MAS (doc.pdf)](/doc.pdf)

## 2-Voip

## Autor
[Federico Manzano](http://github.com/FedeManzano)


