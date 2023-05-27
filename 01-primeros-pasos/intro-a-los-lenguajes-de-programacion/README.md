# PRIMEROS PASOS

## PARA SEGUIR ESTE CURSO VAS A NECESITAR LAS SIGUIENTES HERRAMIENTAS

## INTRO A LOS LENGUAJES DE PROGRAMACIÓN

Los lenguajes de programación son idiomas que las computadoras entienden.Al igual que las personas usamos el español o el inglés para comunicarnos, los programadores utilizan lenguajes de programación para dar instrucciones a las computadoras.
En esta sección vamos a cubrir los conceptos básicos que se aplican a la mayoría de los lenguajes de programación modernos

## LO QUE VAMOS A VER

1.  ¿Qué es la programación?
2.  Tipos de lenguajes de programación
3.  Elementos básicos de un programa

## ¿Qué ES LA PROGRAMACIÓN?

La programación, también conocida como codificación, es darle instrucciones a una computadora. Imagina que eres el jefe y la computadora es tu asistente, y necesitas decirle exactamente qué hacer.  
Para hacer esto, utilizamos un lenguaje de programación. Es como un idioma especial que las computadoras entienden. En lugar de hablar en español o inglés, escribimos en este lenguaje especial para decirle a la computadora qué hacer.  
Cuando escribimos un conjunto de instrucciones usando este lenguaje de programación, se le llama programa, programa de computadora, aplicación (app) o ejecutable.

**¿Que es un programa?**  
Un programa es una serie de instrucciones que la computadora las ejecuta paso a paso. Puede ser un sitio web que visitas, un juego que juegas en tu dispositivo o una aplicación que usas en tu teléfono. Incluso el programa que muestra esta lección en tu pantalla es un programa.

**¿Podemos crear un programa sin escribir código?**  
Es posible crear programas sin escribir código directamente. En su lugar, utilizamos la lógica subyacente, que son reglas e instrucciones escritas en código que alguién mas escribió, pero no las vemos. El dispositivo interpreta esa lógica y realiza las acciones correspondientes.

## TIPOS DE LENGUAJES DE PROGRAMACIÓN

Antes de conocer los diferentes tipos de lenguajes de programación, es necesario saber **¿Qué son los lenguajes de programación?** Un lenguaje de programación es un conjunto de reglas y palabras especiales que podemos utilizar para dar instrucciones a una computadora. Es decir, Los lenguajes de programación nos permiten dar órdenes a la computadora para que realice diferentes tareas, como hacer cálculos, manipular datos, crear páginas web, diseñar videojuegos y mucho más.  
Existen muchos lenguajes de programación diferentes, cada uno con sus propias características y propósitos. Por ejemplo, JavaScript se usa principalmente para aplicaciones web, mientras que Bash se usa principalmente para sistemas operativos.

Además de los lenguajes de programación, existe un nivel más bajo llamado lenguaje de bajo nivel o ensamblador, y aún más abajo se encuentra el código máquina, también conocido como código binario. Estos lenguajes y códigos interactúan entre sí en conjunto con el hardware del dispositivo. Permíteme explicarlo con más detalle:

Imagina que quieres escribir un programa en un lenguaje de programación como Python para sumar dos números. Aquí tienes un ejemplo en Python:
~~~
let a = 5;  
let b = 3;  
let suma = a + b;
console.log(suma);
~~~

Este código en JavaScript es fácil de entender para nosotros los humanos, ¿verdad? Pero, en realidad, la computadora no entiende directamente este código. Necesitamos convertirlo a código máquina, y aquí es donde entra el lenguaje ensamblador.  
El código en JavaScript se traduce a instrucciones en lenguaje ensamblador, que luego se traducen al código máquina que el procesador de la computadora puede entender. El código ensamblador resultante podría verse así:

~~~
mov eax, 5  
mov ebx, 3  
add eax, ebx  
mov ecx, eax 
~~~
 
En este código ensamblador, utilizamos instrucciones especiales como "mov" (mover) y "add" (sumar) para realizar las operaciones necesarias. Estas instrucciones le dicen al procesador qué hacer con los datos.

Luego, este código ensamblador se traduce a código máquina, que es una secuencia de unos y ceros que representa las instrucciones específicas que el procesador ejecutará.

Finalmente, cuando ejecutamos el programa, el procesador lee y ejecuta las instrucciones en código máquina.

El hardware del dispositivo, como el procesador y la memoria, juega un papel fundamental en la ejecución de estas instrucciones. El hardware está diseñado para comprender y ejecutar el código máquina, siguiendo las instrucciones paso a paso.

**En resumen:**, los lenguajes de programación, el lenguaje de bajo nivel, el código máquina y el hardware interactúan entre sí para permitir que los programas escritos por los humanos se ejecuten en las computadoras. Los lenguajes de programación actúan como una capa de abstracción que nos permite expresar nuestras ideas de manera más comprensible, y luego se traducen al lenguaje de la máquina para que el hardware pueda llevar a cabo las instrucciones.

<p align="center">
  <img src="/assets/lenguajes.png" alt="Lenguajes en la computación" style="width: 350px; height: auto;"/>
</p>
