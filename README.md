# semana-3-jorge-garrido-
Creación y conexión de dos maquinas virtuales en VirtualBox
Lo primero que he hecho ha sido descargar el programa de VirtualBox, luego he buscado una version estable de ubuntu, he accedido a la pagina oficial de ubuntu y he descargado la iso, en mi caso ha sido la version 24.04 LTS (Noble Numbat) de 64 bit.
Lo primero que he hecho ha sido crear las maquinas virtuales e indicar que la conexion seria mediante un enlace tipo bridge. He instalado el sistema operativo de ubuntu, ya dentro de la maquina, he entrado en la terminal y he visto las direcciones ip mediante el comando "ip a", he apuntado, las direcciones ip de ambas maquinas, y la mascara de subred y puerto de enlace de una de ellas, he configurado las direcciones ip estaticas de ambas maquinas, he comprobado las direcciones ip de nuevo, para ver si habian cambiado y he comprobado si estaban conectadas mediante el comando "ping", que efectivamente, no daba ningun error.


<img width="1366" height="768" alt="NETPLAN VM1" src="https://github.com/user-attachments/assets/42cac34d-ab97-464d-b6ff-cbaed1c55646" />

<img width="1366" height="768" alt="NETPLAN VM2" src="https://github.com/user-attachments/assets/b0d48e97-6922-45ec-897f-6ed840384a7b" />

<img width="1366" height="768" alt="PING 1" src="https://github.com/user-attachments/assets/e10be996-d78f-4c18-ac84-47e305d99dba" />

<img width="1366" height="768" alt="PING 2" src="https://github.com/user-attachments/assets/86eef16a-6704-4782-a76e-9fcdd497de7d" />

<img width="1366" height="768" alt="IP A 1" src="https://github.com/user-attachments/assets/102d3db3-24f2-43dd-8f92-c794cedcdaff" />

<img width="1366" height="768" alt="IP A 2" src="https://github.com/user-attachments/assets/c14c9174-3203-4a33-aeec-85705a261039" />
