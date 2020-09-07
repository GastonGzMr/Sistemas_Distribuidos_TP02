# Sistemas_Distribuidos_TP02
Este repositorio contiene las clases en java correspondientes a la parte práctica del Trabajo Práctico 02 de la materia 
Sistemas Distribuidos: "Comunicación en Sistemas Distribuidos".
Cada carpeta contiene las clases que resuelven cada ejercicio


1. Utilice la interfaz socket con servicio de datagramas para enviar y recibir mensajes de texto entre dos computadoras.

La carpeta del Ejercicio 1 contiene 2 clases, las cuales emplean sockets de UDP para enviar y recibir un mensaje entre sí
al ser ejecutadas.


2. Implemente un protocolo petición-respuesta para la comunicación entre dos procesos utilizando
sockets. Implementar protocolos de 2,3 y 4 vías. Considere que cada proceso envía y recibe
mensajes en puertos distintos. 

En la carpeta correspondiente a este punto se encuentran clases que simulan el funcionamiento de clientes y servidores de
2, 3 y 4 vías al ejecutarlas. Funcionan con sockets UDP.


3. Implemente una interfaz de comunicación confiable con sockets TCP. 

Las clases en la carpeta Ejercicio 3 simulan l funcionamiento de un cliente y un servidor con un protocolo de petición y
respuesta de 3 vías cuando se las ejecuta. Funcionan con sockets TCP.
