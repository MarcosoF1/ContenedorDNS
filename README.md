# ContenedorDNS

-Especifico la versión del docker compose -->version: '2'

-Esto sera el nombre de la imagen  -->asir_bind:

-Esta es la imagen que se utilizara-->  image: internetsystemsconsortium/bind9:9.16
    
-Sirve para hacer una relacion de puertos, donde pongo el puerto de mi maquina para acceder al contenedor y el puerto al que va al contenedor-->  ports:
      
-Con esto puedo crear volumenes y vincularlos a una carpeta de un contenedor--> volumes:
