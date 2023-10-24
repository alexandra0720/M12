# M12
Practica-grupo-3
# Clasificación de IP's

En el mundo de las redes informáticas, las direcciones IP desempeñan un papel fundamental. Las direcciones IP se utilizan para identificar dispositivos en una red y enrutar datos entre ellos. A continuación, se detallarán varios aspectos relacionados con las direcciones IP:

## Uso de IP's para Servidores y Puertas de Enlace

- Las direcciones IP se dividen en dos categorías principales: IPv4 e IPv6. Las direcciones IPv4 son las más comunes y están formadas por 32 bits, mientras que las direcciones IPv6 son más nuevas y utilizan 128 bits.
- Las direcciones IP se asignan a servidores y dispositivos de red para que puedan comunicarse en una red. Los servidores suelen tener direcciones IP estáticas, mientras que los dispositivos finales como computadoras y teléfonos suelen obtener direcciones IP dinámicas a través de un servidor DHCP.
- Las puertas de enlace, también conocidas como routers, utilizan direcciones IP para enrutar el tráfico entre redes diferentes. La puerta de enlace predeterminada de una red suele ser la dirección IP del router que conecta esa red con otras.

## Función de las Máscaras de Red y Cálculo según la Clasificación de IP's

- Las máscaras de red se utilizan para dividir una dirección IP en dos partes: la parte de red y la parte de host. La máscara de red se representa como una serie de bits "1" seguidos de una serie de bits "0". Por ejemplo, en una máscara de red de 255.255.255.0, los primeros 24 bits se utilizan para la red y los últimos 8 bits para los hosts.
- El cálculo de la máscara de red y la división de IP en parte de red y parte de host depende de la clase de dirección IP. Las direcciones IP se dividen en clases A, B, C, D y E, y cada clase tiene una máscara de red predeterminada asociada.

## VLAN (Red de Área Local Virtual)

- Una VLAN es una red de área local virtual que se utiliza para segmentar una red física en múltiples redes lógicas. Esto permite separar tráfico, mejorar la seguridad y optimizar el rendimiento de la red.
- En Packet Tracer, una herramienta de simulación de redes, puedes configurar VLANs en switches y enrutadores. Debes asignar puertos a VLANs específicas y configurar las interfaces de enrutador para permitir el enrutamiento entre VLANs.

## Configuración de Red en Máquinas Virtuales

- En entornos de máquinas virtuales, puedes configurar diferentes adaptadores de red para lograr diversos objetivos. Algunas configuraciones comunes incluyen adaptadores de red puente, adaptadores NAT y adaptadores de red interna.
- La elección de la configuración de adaptador de red depende de la conectividad que necesites en tus máquinas virtuales y de la infraestructura de red de tu sistema de virtualización.

## Configuración de Red en Windows

- En el sistema operativo Windows, puedes configurar la red a través del Panel de Control o la Configuración de Red e Internet. Puedes asignar direcciones IP, configurar adaptadores de red y administrar la conexión a redes cableadas o inalámbricas.

## Configuración de Red en Linux (Debian y Ubuntu 22.04)

- En sistemas Linux, como Debian y Ubuntu 22.04, la configuración de red se realiza principalmente a través del archivo de configuración `/etc/network/interfaces`. Puedes asignar direcciones IP, configurar interfaces de red y definir rutas estáticas en este archivo.
- Además, puedes utilizar comandos como `ifconfig`, `ip`, `nmcli` y `systemctl` para administrar y configurar la red en sistemas Linux.

Es importante comprender estos conceptos y configuraciones para administrar eficazmente una red y asegurarse de que los dispositivos se comuniquen correctamente.

