Tema 1 — Introducción a Java

1. Qué es Java
Java es un lenguaje de programación.
Sirve para decirle al ordenador qué tiene que hacer mediante instrucciones.
Un programa Java está formado por:
clases
métodos
instrucciones
variables
datos
Cuando empiezas, lo más importante es entender esto:
un programa es una secuencia de instrucciones que se ejecutan en orden
Ejemplo mental:
guardar un número
guardar otro número
sumarlos
mostrar el resultado
Eso ya es programar.

2. Qué necesitas en IntelliJ
Para trabajar en IntelliJ necesitas:
IntelliJ instalado
Java JDK instalado
Si IntelliJ ya te abre proyectos Java, seguramente ya lo tienes bien.
Comprueba esto en IntelliJ
Abre IntelliJ y mira si puedes crear:
New Project → Java
Si te deja elegir versión de JDK, perfecto.
Si no te aparece Java o JDK, te ayudo a configurarlo luego.

3. Crear tu primer proyecto en IntelliJ
Haz esto:
abre IntelliJ
pulsa New Project
elige Java
nombre del proyecto:

00-introduccion-java

elige una carpeta donde guardarlo
pulsa Create

4. Qué verás en el proyecto
Normalmente tendrás una carpeta src.
Dentro de src es donde pondremos las clases Java.
Vamos a crear una clase llamada Main.
Haz clic derecho sobre src:
New → Java Class
Nombre:

Main


5. Estructura básica de un programa Java
Escribe esto:

public class Main {
    public static void main(String[] args) {
        System.out.println("Hola, mundo");
    }
}

Qué significa cada parte
public class Main
Aquí defines una clase llamada Main.
La clase es como el contenedor del programa.
public static void main(String[] args)
Es el método principal.
Es el punto por donde empieza la ejecución del programa.
System.out.println("Hola, mundo");
Muestra texto por pantalla.

6. Primer objetivo práctico
Ejecuta el programa.
En IntelliJ:
botón verde de ejecutar
o clic derecho sobre Main → Run
Debes ver abajo:

Hola, mundo

Si eso sale, ya has hecho tu primer programa Java.

7. Teoría importante: salida por pantalla
Para mostrar texto usamos:

System.out.println("texto");

println significa que imprime y luego baja de línea.
Ejemplos:

System.out.println("Me llamo Myriam");
System.out.println("Estoy estudiando DAW");
System.out.println("Java es mi primer lenguaje");

8. Muy importante: diferencia entre texto y código
Cuando escribes esto:

System.out.println("Hola");

"Hola" es texto literal.
Pero esto:

System.out.println(5);

es un número.
Java distingue los tipos de datos. Eso lo veremos en el siguiente bloque.

9. Errores típicos al empezar
Los más comunes son:
Olvidar el ;
Mal:

System.out.println("Hola")

Bien:

System.out.println("Hola");

Escribir mal main
Debe ser exactamente así:

public static void main(String[] args)

Poner comillas mal
Mal:

System.out.println(Hola);

Bien:

System.out.println("Hola");




