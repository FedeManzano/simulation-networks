

# :earth_americas: Redes Informáticas 
A continuación se detallan los requisitos necesarios para trabajar con este repositorio:

## :pushpin: Requisitos

- Cisco Packet Tracer 8.2.2.0400 o superior
- Visualizador de archivos .pkt (Packet Tracer)
- Visualizador de archivos .eddx (EdrawMax) para planos físicos (opcional)
- Visualizador de archivos PDF para la documentación


A través del ```Packet Tracer 8.2.2.0400``` se incluirán un conjunto de temas relacionados con la configuración de ```redes informáticas```. Toda la documentación del proyecto se puede ver aquí <b>:green_book: [Documentación PDF](doc.pdf)</b>

 
 ## :information_source: Recursos externos

- [CISCO Packet Tracer 8.2.2.0400](https://www.netacad.com/es/articles/news/download-cisco-packet-tracer)
- [Imagen de la portada](https://www.netacad.com/)
- [Plano E-Draw-Max](https://www.edrawmax.com/)

## :clipboard: Recorrido
- :file_folder: [Estructura](#file_folder-estructura)
- :zero: [Introducción](#zero-introducción)
- :arrow_right: [1-LAN](#arrow_right-1-lan)
- :telephone: [2-Voip](#telephone-2-voip)
- :arrow_heading_up: [Ruta Estática](#arrow_heading_up-ruta-estática)
- :recycle: [Redundancias](#file_folder-estructura)
- :on: [Etherchannel](#file_folder-estructura)
- :european_post_office: [Capa Física](#file_folder-estructura)
- :arrow_heading_up: [Enrutamiento](#file_folder-estructura)
- :globe_with_meridians: [Api-Rest](#file_folder-estructura)
- :man_with_gua_pi_mao: [Autor](#man_with_gua_pi_mao-autor)

## :file_folder: Estructura

1. <b>:open_file_folder: Lan</b>
    * <i>:page_facing_up: lan-simple.pkt</i>
    * <i>:page_facing_up: lan-dos-vlans-dhcp.pkt</i>
    * <i>:page_facing_up: lan-dos-vlans-cruzadas.pkt</i>
2. <b>:open_file_folder: Voip</b>
    * <i>:page_facing_up: voip-comunicacion-lan.pkt</i>
    * <i>:page_facing_up: voip-conexion-serial.pkt</i>
    * <i>:page_facing_up: voip-dial-peer.pkt</i>
3. <b>:open_file_folder: Rutas-Estáticas</b>
    * <i>:page_facing_up: rs-ruta-default.pkt</i>
    * <i>:page_facing_up: rs-ruta-estática.pkt</i>
    * <i>:page_facing_up: rs-ruta-flotante.pkt</i>
4. <b>:open_file_folder: Redundancias</b>
    * <i>:page_facing_up: red-un-enlace-dos-capas.pkt</i>
    * <i>:page_facing_up: red-dos-enlaces-dos-capas.pkt</i>
    * <i>:page_facing_up: red-dos-enlaces-tres-capas.pkt</i>
5.  <b>:open_file_folder: Etherchannel</b>
    * <i>:page_facing_up: eth-tres-enlaces.pkt</i>
6. <b>:open_file_folder: Capa Física</b>
    * <b>:open_file_folder: presupuesto</b>
        * <i>:page_facing_up: presupuesto.txt</i>
    * <i>:page_facing_up: fisica-sucursal.pkt</i>
    * <i>:page_facing_up: plano_fisico.eddx</i>
    * <i>:page_facing_up: plano-fisico.png</i>
15. <b>:green_book: [Documentación PDF](doc.pdf)</b>

## :zero: Introducción

Proyectos realizados en el simulador de redes de [CISCO](https://www.cisco.com/site/ar/es/index.html). A lo largo de este trabajo se verán temas relacionados con los conceptos más importantes de las redes de computadoras (Voip, rutas estáticas, rutas dinámicas, redundancias, Switching, capas, etcétera). <br>
Para todas las redes definidas en todos los ejercicios de este trabajo, se toman las IPv4 como una SUBNET de 160.15. XX. [SSSS] HHHH donde XX es el número de VLAN elegido para la red, SSSS es el SUBNETID y HHHH es el espacio de direccionamiento para los hosts, en este caso 2^4 = 16 HOSTS por VLAN.

:green_book: [...MAS (doc.pdf)](/doc.pdf)


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

## :arrow_heading_up: Ruta Estática
Proximamente...

:green_book: [...MAS (doc.pdf)](/doc.pdf)

## :man_with_gua_pi_mao: Autor
[Federico Manzano](http://github.com/FedeManzano)


