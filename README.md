# USART
Programa de prueba con la USART

Enunciado

En los dos ensayos, que seguidamente se describen, debe configurarse la USART para trabajar a 9600 baudios con 8 bits de datos.

- Programa 1. Debe desarrollarse un programa que escriba una letra (siempre la misma) por medio de la USART dentro de un bucle infinito.
- Programa 2. Debe desarrollarse un programa que escriba la palabra “Hola”, con salto de linea y control de carro al final de la palabra, utilizando el servicio printf de stdio.h [printf(“Hola\z\n”);]

Para este último caso debe leerse con atención, del manual MPLAB XC8 C Compiler User Guide (puede encontrarse en el directorio /opt/microchip/xc8/{version}/docs y en el directorio “Documentación general” del moodle de la asignatura), el apartado 2.5.8 (en la versión 2.00), o el apartado 3.4.8 (en la versión 2.20). También, para este último caso, se suministra también una plantilla de solución en el moodle de la asignatura.

En concreto, hay que tener en cuenta que printf invoca, para imprimir cada carácter, a la función “putch”, la cual debe adaptarse según sea el dispositivo por el que pretende enviarse los caracteres a imprimir. En el apartado del manual, indicado en el párrafo anterior, el fabricante pone un ejemplo.
