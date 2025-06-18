# Proyecto final_con_docker_compose
Panel de Admistración del sistema de venta en Php y Mysql
![sis](https://user-images.githubusercontent.com/88554898/128939852-572098b6-762e-4274-96c5-d36966422fff.jpg)

Plantilla Utilizada
https://github.com/creativetimofficial/material-dashboard

## Para levantar el contenedor ejecuta los siguientes comandos desde tu terminal:

$git clone https://github.com/Ironcapi/final.git

$cd final/

$docker compose up -d

## Una vez ejecutados los comandos ingresa a localhost desde tu navegador al puerto 86

http://localhost:86/

Usuario: admin

contraseña: admin

## Si desea ingresar a la base de datos desde la terminal utiliza los siguientes comandos:

$docker exec -it mariadb-container bash

$mysql -u root -p -h localhost

Contaseña de root: root



