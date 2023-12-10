# Peaje

En una estación de peaje en La Mesa, la registradora utilizada por la administradora sufrió una avería, generando un problema para llevar el control diario de automóviles, buses y camiones pesados. El supervisor del peaje expresó su molestia al enterarse de que la reparación de la registradora llevará n días. Ante la imposibilidad de "cuadrar caja" durante este periodo, el supervisor le pidió a la administradora, al finalizar su jornada, que se acercara con los tiquetes y el dinero recaudado para realizar el cuadre de caja de forma manual.

Se necesita desarrollar un programa en C/C++ que permita ingresar el dinero total entregado por la administradora por día, así como los tipos de tiquetes emitidos durante su jornada laboral. El programa debe mostrar un mensaje indicando si el cierre de caja fue exitoso o no. Un cierre exitoso ocurre cuando la suma del valor de los tiquetes es igual al total de dinero entregado por la administradora.

Los precios de los tiquetes son los siguientes:
- Tipo A (Automóviles): $5000
- Tipo B (Buses): $7500
- Tipo C (Camiones): $18000

Por ejemplo, si la administradora entrega al final del día:
- Dinero entregado: $50.500
- Tiquetes registrados: A, B, B, C, A

Este NO es un cierre de caja exitoso, ya que la suma del valor de los tiquetes registrados ($43.000) no coincide con el dinero entregado, resultando en un descuadre de $7.500.

Además, el programa debe responder las siguientes preguntas para el periodo de n días:
a. ¿Cuál fue el valor total vendido por cada tipo de tiquete en el mes?
b. ¿En qué día se presentó el mayor descuadre y cuál fue su monto?
c. ¿Cuánto fue el total del descuadre en el mes?
d. ¿Cuál fue el porcentaje vendido por tipo de tiquete en el mes?

El programa debe hacer uso del condicional múltiple excluyente para evaluar las condiciones del cierre de caja.
