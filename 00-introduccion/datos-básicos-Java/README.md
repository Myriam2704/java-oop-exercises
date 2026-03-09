Tipos de datos básicos en Java
Los tipos de datos sirven para guardar información en variables.
1. int
Sirve para guardar números enteros.
Ejemplos:

int edad = 20;
int numero = 15;
int alumnos = 30;

No puede tener decimales.
Correcto:

5
10
-3
100

Incorrecto:

3.5
7.2


2. double
Sirve para guardar números decimales.
Ejemplo:

double precio = 19.99;
double altura = 1.75;
double temperatura = 23.5;


3. char
Sirve para guardar un solo carácter.
Se escribe con comillas simples.
Ejemplo:

char letra = 'A';
char inicial = 'M';
char simbolo = '#';

Esto es incorrecto porque hay más de un carácter:

char texto = 'Hola'; // error


4. boolean
Sirve para guardar verdadero o falso.
Solo puede tener dos valores:

true
false

Ejemplo:

boolean mayorEdad = true;
boolean aprobado = false;


5. String
Sirve para guardar texto o cadenas de caracteres.
Se escribe con comillas dobles.
Ejemplo:

String nombre = "Myriam";
String ciudad = "Murcia";
String mensaje = "Hola mundo";


Diferencia importante

char = un carácter String = texto completo

Ejercicio para practicar (nivel FP)
Crea una clase llamada:

EjercicioVariables

y escribe este programa:

public class EjercicioVariables {

    public static void main(String[] args) {

        int edad = 20;
        double altura = 1.68;
        char inicial = 'M';
        boolean estudiante = true;
        String nombre = "Myriam";

        System.out.println(nombre);
        System.out.println(edad);
        System.out.println(altura);
        System.out.println(inicial);
        System.out.println(estudiante);

    }

}
