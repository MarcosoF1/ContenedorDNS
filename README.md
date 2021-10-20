# ContenedorDNS

- Especifico la versión del docker compose -->version: '2'

- Esto sera el nombre de la imagen  -->asir_bind:

- Esta es la imagen que se utilizara-->  image: internetsystemsconsortium/bind9:9.16
    
- Sirve para hacer una relacion de puertos, donde pongo el puerto de mi maquina para acceder al contenedor y el puerto al que va al contenedor-->  ports:
      
- Con esto puedo crear volumenes y vincularlos a una carpeta de un contenedor--> volumes:

# Instalacion comandos necesarios:

- Lo primero que tenemos que hacer es un apt update

## Instalación Ping:

- apt install iputils-ping

## Instalación  tracepath  &  traceroute

- apt-get install iputils-tracepath

- apt-get install traceroute

## Instalación  mtr

- apt-get -y install mtr

## Instalación  ifconfig

- sudo apt install net-tools

## Instalación  ifdown & ifup

- apt-get install -y ifupdown

## Instalación ip address show

- apt install iproute2

## Instalación  host

- apt install host

## Instalación route

- apt install net-tools

## Instalación ifplugstatus

- apt-get install -y ifplugd

## Instalación dhclient

- apt-get install isc-dhcp-client

## Instalación netstat

- apt install net-tools

## Instalación whois

- apt install whois

## Instalación curl & wget

- apt install curl

- apt install wget