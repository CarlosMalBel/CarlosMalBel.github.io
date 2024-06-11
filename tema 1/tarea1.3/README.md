# Actividad 1.3 Servidor LAMP


### Parte 1: Instalacion de MariaDB, Apache y PHP.

- Para esta primera parte seguimos el pdf que nos indica la tarea, [PDF con lo comandos](LAMP y LEMP version 1), en donde nos detalla paso a paso y comando a comando como instalar primero Apache2 y PHP.
- Al final de seguir los pasos comprobamos que tenemos instalado Apahe2 y PHP buscando en el buscador `http://ip_de_la_maquinaAWS/info.php` y nos saldra lo siguiente:
  [Prueba-php/apache2](img/php.PNG)


### Parte 2: Instalacion de Wordpress.

- En esta parte para instalar Wordpress tambien seguimos el [PDF con las instruciones](tema 1/tarea1.3/LAMP y LEMP version 1.pdf) y al final hacemos lo mismo que en la parte 1, introducimos en el buscador `http://ip_del_servidor/wp-admin` y nos saldra:
  [2](img/2.PNG)

- En esta parte le damos a donde dice vamos y nos saldra las opciones para crear el sitio wordpress:
  [3](img/3.PNG)

  ### Parte 3: Instalación de Wordpress usando contenedores Docker y Docker Compose.

  - En esta ultima parte tenemos que primero instalar docker mediante los comandos recogidos en: [Tutorial para instalar docker](tema 1/tarea1.3/Instalacion docker y docker-compose linux 202324 UBUNTU.txt), una vez instalado dockers clonamos el repositorio de [Git-hub](https://github.com/CarlosMalBel/docker-compose-playground) e iniciamos el ejemplo número 15, no sin antes cambiar en el `.env` de "alumno200" al numero que corresponda segun el usuario del dominio, en mi caso el 21. Por lo que quedaria de tal forma:
[Variables editadas](img/1.PNG)

- Ahora con esto cambiado, introducimos el comando ```docker compose up -d``` para inciar los servicios y al igual que con las otras partes, para entrar en wordpress introducimos `http://ip_de_la_maquina/wp-admin`:
  [5](5.PNG)
