<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Se utiliza una serie de flip flops encadenados en forma de shift register, que a través de botones permiten ingresar una combinación binaria que de ser correcta enciende un led. La combinación correcta depende de la configuración del bloque, que toma 8 inputs y los convierte en 1 output. Esto sucede a través de concatenación de puertas AND y el uso de algunos NOT para definir la combinación correcta. En este caso la contraseña es 01111111, por lo que solo se usa un NOT en el primer input (para que 0 se convierta en 1 antes de entrar a las compuertas AND).

## How to test

Para ingresar, se debe apretar el botón step (letra S en el teclado), y añadirá un 0, si al apretar el botón, se encuentra el INGRESAR (barra espaciadora) apretado, se ingresará un 1.
De esta manera, para ingresar la combinación correcta, se deberá:
1) Apretar reset
2) Presionar step (S)
3) Presionar y mantener presionado ingresar (ESPACIO)
4) Presionar 7 veces step (S), mientras se mantiene presionado INGRESAR
Es necesario el uso de un teclado, ya que se necesitan apretar dos botones a la vez.

El número ingresado deberá ser 01111111
## External hardware

N/A
