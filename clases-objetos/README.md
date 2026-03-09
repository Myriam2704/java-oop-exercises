# Clases y objetos

1. Qué es una clase 

Una clase es un molde para crear objetos.

Ejemplo real:

Clase	        Objeto
Persona	      Myriam
Coche	        mi coche
Libro	        un libro concreto

La clase define:

atributos → datos

métodos → acciones

Ejemplo:

Clase Persona

Atributos:

nombre
edad
altura

Métodos:

saludar()
cumplirAnios()

2. Primera clase sencilla

Crea un archivo nuevo en IntelliJ:

Persona.java

Código:

public class Persona {

    String nombre;
    int edad;
    double altura;

}

Esto crea una clase con atributos.

3. Crear un objeto de esa clase

Ahora modifica Main.java.

public class Main {

    public static void main(String[] args) {

        Persona persona1 = new Persona();

        persona1.nombre = "Myriam";
        persona1.edad = 35;
        persona1.altura = 1.65;

        System.out.println(persona1.nombre);
        System.out.println(persona1.edad);
        System.out.println(persona1.altura);

    }

}

4. Qué está pasando aquí
Crear objeto
Persona persona1 = new Persona();

Significa:

tipo   nombreObjeto   constructor
Asignar valores
persona1.nombre = "Myriam";

Accedemos al atributo con:

objeto.atributo


5. Resultado en consola
Myriam
35
1.65

7. Ahora tú.
Ejercicio 

Crea una clase:

Libro

Atributos:

titulo
autor
paginas

Luego en Main:

Crea un objeto libro

Asigna valores

Imprime los datos

Resultado esperado:

Titulo: El Quijote
Autor: Cervantes
Paginas: 863
