# PRIMEROS PASOS

## PARA SEGUIR ESTE CURSO VAS A NECESITAR LAS SIGUIENTES HERRAMIENTAS  

Para programar, necesitarás varias herramientas que te ayudarán a escribir, compilar, depurar y ejecutar tus programas. Aquí hay una lista de herramientas básicas que son comunes en el proceso de programación.

+ **Editor de texto o Entorno de Desarrollo Integrado (IDE)** Necesitarás un lugar para escribir tu código. Puedes usar un editor de texto simple, como Notepad o Sublime Text, o un IDE más completo, como Visual Studio Code, PyCharm o Eclipse. Estas herramientas te proporcionan resaltado de sintaxis, sugerencias de código y otras características útiles para facilitar la escritura de programas.

+ **Compilador o intérprete:** Dependiendo del lenguaje de programación que estés utilizando, necesitarás un compilador o un intérprete. Un compilador traduce tu código fuente a un lenguaje de bajo nivel que la computadora puede entender y ejecutar directamente. Por otro lado, un intérprete lee y ejecuta el código línea por línea. Algunos lenguajes, como Python y JavaScript, utilizan intérpretes, mientras que otros, como C++ y Java, utilizan compiladores.
**¿Cúal es la diferencia entre un compilador y un interpréte?** La diferencia fundamental entre un compilador y un intérprete radica en cómo se traduce y ejecuta el código. Un compilador traduce todo el programa de una vez a un lenguaje de bajo nivel antes de su ejecución, mientras que un intérprete lee y ejecuta el código línea por línea en tiempo real.

+ **Depurador**: Un depurador es una herramienta que te permite ejecutar tu programa paso a paso y realizar un seguimiento del flujo de ejecución y los valores de las variables. Te ayuda a identificar y corregir errores en tu código (también conocidos como bugs). Generalmente los IDEs incluyen depuradores integrados.

+ **Control de versiones:** El control de versiones es una herramienta que te permite realizar un seguimiento de los cambios en tu código a lo largo del tiempo. Puedes revertir cambios, colaborar con otros programadores y mantener un historial de tus modificaciones. **Git es una de las herramientas de control de versiones más populares.**

+ **Documentación y recursos en línea:** Es una herramienta fundamental para los desarrolladores, ya que les proporciona información detallada sobre cómo utilizar herramientas y lenguajes de programación. Es como un mapa que los guía en su aprendizaje y les permite comprender el funcionamiento interno. La documentación les ayuda a evitar errores, resolver dudas y aprovechar al máximo las capacidades de las herramientas que están utilizando. Es una guía paso a paso, disponible en diferentes formatos, que les permite explorar nuevas tecnologías y profundizar en su conocimiento.

+ **Línea de comandos:** La línea de comandos es una interfaz de texto donde los desarrolladores pueden interactuar directamente con su sistema operativo. Proporciona comandos y herramientas que permiten ejecutar programas, automatizar tareas y administrar archivos y directorios. A través de la línea de comandos, los desarrolladores pueden compilar, ejecutar y depurar programas, así como realizar otras operaciones relacionadas con el desarrollo.

+ **Los navegadores web** Son herramientas esenciales para la programación en desarrollo web. 
Permiten visualizar y ejecutar aplicaciones web, facilitando la identificación y corrección de errores, pruebas de rendimiento y optimización de código. Además, son útiles para probar el diseño y comportamiento de un sitio web en diferentes dispositivos y tamaños de pantalla. Proporcionan un entorno interactivo para experimentar con nuevas tecnologías y aprender conceptos de programación web. También ayudan a verificar la compatibilidad de un sitio web en diferentes navegadores y versiones. 

🪧 En la próxima sección **Instalando herramientas fundamentales** configuraremos las herramientas necesarias y exploraremos las más utilizadas en programación!
## INTRO A LOS LENGUAJES DE PROGRAMACIÓN

Los lenguajes de programación son idiomas que las computadoras entienden.Al igual que las personas usamos el español o el inglés para comunicarnos, los programadores utilizan lenguajes de programación para dar instrucciones a las computadoras.
En esta sección vamos a cubrir los conceptos básicos que se aplican a la mayoría de los lenguajes de programación modernos

## LO QUE VAMOS A VER

1.  ¿Qué es la programación?
2.  Tipos de lenguajes de programación
3.  Elementos básicos de un programa

## ¿QUÉ ES LA PROGRAMACIÓN?
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

Imagina que quieres escribir un programa en un lenguaje de programación como JavaScript para sumar dos números. Aquí tienes un ejemplo en JavaScript:
~~~
let a = 5;  
let b = 3;  
let suma = a + b;
console.log(suma);
~~~

Este código en JavaScript es fácil de entender para nosotros los humanos, ¿verdad? Pero, en realidad, la computadora no entiende directamente este código. Necesitamos convertirlo a código máquina, y aquí es donde entra el lenguaje de bajo nivel o ensamblador.El código en JavaScript se traduce a instrucciones en lenguaje de bajo nivel , que luego se traducen al código máquina que el procesador de la computadora puede entender. El código en bajo nivel resultante podría verse así:

~~~
mov eax, 5  
mov ebx, 3  
add eax, ebx  
mov ecx, eax 
~~~
 
En este código ensamblador, utilizamos instrucciones especiales como "mov" (mover) y "add" (sumar) para realizar las operaciones necesarias. Estas instrucciones le dicen al procesador qué hacer con los datos.

Luego, este código en lenguaje de bajo nivel se traduce a código máquina o binario, que es una secuencia de unos y ceros que representa las instrucciones específicas que el procesador ejecutará.

Finalmente, cuando ejecutamos el programa, el procesador lee y ejecuta las instrucciones en código máquina.

El hardware del dispositivo está diseñado para comprender y ejecutar el código máquina, siguiendo las instrucciones paso a paso.

**En resumen:**, el lenguaje de programación nos permite escribir código en un formato fácil de entender para nosotros los humanos. Luego, ese código se traduce al lenguaje ensamblador, que es más cercano al funcionamiento de la máquina. Finalmente, el código ensamblador se traduce al código máquina, que es lo que el procesador puede ejecutar directamente.

<p align="center">
  <img src="/assets/lenguajes.png" alt="Lenguajes en la computación" style="width: 350px; height: auto;"/>
</p>

## ELEMENTOS BÁSICOS DE UN PROGRAMA

**¿Cuáles son los elementos que forman a un programa?**  
Los elementos básicos de un programa de computadora pueden variar dependiendo del lenguaje de programación utilizado, pero en general, existen algunos componentes comunes que se encuentran en la mayoría de los programas. Aquí están los elementos básicos:
1. **Instrucciones:** Un programa consiste en una secuencia de instrucciones que le indican a la computadora qué hacer. Estas instrucciones pueden ser simples, como asignar un valor a una variable, o más complejas, como ejecutar una serie de cálculos o mostrar información en la pantalla.
2. **Variables:** Las variables son contenedores de datos que se utilizan para almacenar información durante la ejecución del programa. Pueden contener valores numéricos, caracteres, texto u otros tipos de datos. Las variables se utilizan para almacenar y manipular datos en un programa.
3. **Estructuras de control:** Las estructuras de control permiten controlar el flujo de ejecución de un programa. Esto incluye estructuras de control condicionales, como instrucciones "if" (si) y "else" (sino), que permiten tomar decisiones basadas en el resultado de una compración (Si es verdadero, hace esto - Si es falso , finaliza la ejecución o realiza otra acción). También incluye estructuras repetitivas o bucles, como el "for" y "while", que permiten repetir un bloque de código varias veces según la necesidad del programa.
4. **Funciones:** Las funciones son bloques de código que realizan una tarea específica. Permiten dividir un programa en partes más pequeñas y reutilizables, lo que facilita la organización y el mantenimiento del código. Las funciones también pueden recibir argumentos (datos de entrada) y devolver resultados (datos de salida).
5. **Entrada y salida:** Los programas a menudo interactúan con los usuarios o con otros sistemas a través de la entrada y salida de datos. Esto puede incluir la lectura de datos del teclado o de un archivo, la visualización de información en la pantalla o la escritura de datos en un archivo. 


