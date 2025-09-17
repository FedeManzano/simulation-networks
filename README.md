# Proyecto de Redes Informáticas 

<p align="center">
  <img src="imagenes/portada/portada.png" />
</p>

A través del ```Packet Tracer 8.2.2.0400``` se incluirán un conjuno de temas relacionados con la configuración de redes informáticas.

## Recursos

- [CISCO Packet Tracer 8.2.2.0400](https://www.netacad.com/es/articles/news/download-cisco-packet-tracer)
- [Imagen de la portada](https://www.netacad.com/)

## Estrctura

```TXT
| redes_proyectos
  | 1-Lan
    - lan-simple.pkt
    - lan-dos-vlans-dhcp-pht
    - lan-dos-vlans-cruzadas.pkt
  | 2-voip
    - voip-comunicacion-lan.pkt
    - voip-conexion-serial.pkt
    - voip-dial-peer.pkt
```

## Introducción

Proyectos realizados en el simulador de redes de CISCO. A lo largo de este trabajo se verán temas relacionados con los conceptos más importantes de las redes de computadoras (Voip, rutas estáticas, rutas dinámicas, redundancias, switching, capas etc).

## 1-LAN

Para comenzar vamos a realizar ejemplos sencillos de como configurar redes de área local utilizando un SWITCH, un ROUTER y algunos hosts conectados a los dispositivos antes mencionados. 
En el primer ejemplo vamos a ver de qué forma realizar lo propuesto anteriormente a través de un SWITCH modelo 2960 y un ROUTER 4331 con la configuración estática de las IP de los hosts. 
El objetivo es definir distintas VLAN y distribuirlas por los puertos de diferentes SWITCHES con las configuraciones pertinentes para que puedan comunicarse entre sí.

> Todos los ejemplos menos el primero van a utilizar la configuración dinámica de las direcciones IPv4 e IPv6, y generando esquemas de red con VLANs cruzadas a través de rutas estáticas para incrementar la dificultad de los ejercicios.


[...MAS (doc.pdf)](/doc.pdf)

## 2-Voip

## Autor
[Federico Manzano](http://github.com/FedeManzano)


