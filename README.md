Introducción: Proyecto de Calculadoras Alternativas con Tarjeta Nucleo

Este proyecto tiene como objetivo implementar dos calculadoras independientes utilizando una tarjeta Nucleo programada de manera serial y un keypad para la entrada de datos. Las calculadoras operan en dos modos distintos: modo serial, donde se ingresa y recibe un solo dígito, y modo keypad, donde se ingresan y reciben valores de dos dígitos.

Funcionamiento:

Modo Serial:
En este modo, la tarjeta Nucleo está configurada para comunicarse de manera serial, permitiendo ingresar un solo dígito como entrada.
Después de recibir el dígito, la tarjeta realiza la operación matemática correspondiente y devuelve el resultado a través de la comunicación serial.
Esta calculadora es útil para operaciones simples que requieren un solo valor numérico como entrada.
Modo Keypad:
Al cambiar al modo keypad, la tarjeta Nucleo espera la entrada de dos dígitos a través del keypad.
Los dígitos ingresados se utilizan para realizar una operación matemática más compleja, como sumar, restar, multiplicar o dividir.
El resultado de la operación se muestra en un display conectado a la tarjeta, proporcionando una respuesta clara y precisa.

Alternancia de Modos:
Para alternar entre el modo serial y el modo keypad, se ha implementado un botón físico en la tarjeta Nucleo.
Al presionar este botón, el usuario puede cambiar fácilmente entre los dos modos de operación, adaptándose a las necesidades específicas de cada cálculo.
Uso y Contribuciones:

Este repositorio contiene el código fuente y la documentación necesaria para comprender y utilizar este sistema de calculadoras alternativas.

Usando la comunicacion serial RX, TX para poder mandar y transimitir informacion atravez de un ordenador logrando la conexion con la tarjeta nucleo y un elemento externo 

![image](https://github.com/GIRONBR/serial-kpad/assets/144930597/9f64cfa4-b9cf-442a-a6af-9379b44127d6)


Usando un keypad aprendiendo la multiplexacion necesaria para poder utilizar todos los botones que se encuentra entre columna y filas 

![image](https://github.com/GIRONBR/serial-kpad/assets/144930597/82977258-6057-4e36-bff7-40263216a841)






DOCUMENTACION DE SERIAL Y KPAD UTILIZADOS EN EL CODIGO 
https://drive.google.com/file/d/1kYUgE-U0hOPn2uL3F-Hehy9BFtCr-xay/view?usp=sharing

VIDEO DE YOUTUBE 
https://youtu.be/5VOoEO3vf2Y
