# SXE01

## Tabla
![Captura 1](capturas/cap1.png)

## Máquina Virtual
Así queda la primera parte de la máquina virtual. Además, como puse en la tabla, le puse 8192MB de RAM, 2 núcleos y 50GB de disco aunque no se muestra en las imágenes.

![Captura 2](capturas/cap2.png)

## Instalación Ubuntu Server
En esta parte solo muestro la creación del perfil y como marcamos la opción de OpenSSH para realizar las tareas posteriores.

![Captura 3](capturas/cap3.png)
![Captura 4](capturas/cap4.png)

## Conexión a la MV desde el anfitrión
Primero no era capaz de conectarlo así que, le puse un adaptador puente a la MV, pero no me daba IP. Tuve que modificar el .yaml y añadir la interfaz para recibirla. Una vez hecho esto, me conecté
con el comando de ssh nombre_usuario@IP_adaptador.

![Captura 5](capturas/cap5.png)

## Actualización de paquetes e instalación
