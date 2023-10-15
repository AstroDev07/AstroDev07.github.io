# Hola Mundo
A partir de esta nueva lección, comenzaremos a crear crear códigos que de alguna manera sean "Funcionales". Con esto me refiero a que nuestros programas a partir de aquí, realizarán alguna que otra tarea sencilla y, poco a poco, irán aumentando su dificultad.

## ¿Con qué empezaremos?
Ahora, crearemos un *Hola Mundo*, que es el ejemplo que se usa comunmente para desarrollar tu primer programa en cualuier lenguaje. Pero, dejemonos de charla y vamos a chambear...
```cpp
#include <iostream>

int main(){
	printf("%s","Hola Mundo\n")
	return 0;
}
```
```
Output:
Hola Mundo
```
Así es, esto escribe Hola Mundo en la pantalla. No te asustes, la primera vez que lo hice, yo tampoco entendí nada, pero yo te lo explicaré ahora mismo.

## Explicación
Para empezar, creamos la estructura básica del programa que ya estudiamos en lecciones anteriores, declaramos las librerías a usar, creamos la función inicial `main`, y, dentro de ella, agregamos nuestro código.

En este caso, la linea 4, es la encargada de escribir en la pantalla lo que queremos, así que vamos a analizarla.
```cpp
printf("%s", "Hola Mundo");
```
En esta línea, estamos llamando a una función llamada `printf`, la cual es la encargada de imprimir texto en la pantalla. Dentro de los paréntesis de la función, hay 2 argumentos, el primero(`%s`), le dice a la computadora que lo que queremos imprimir es una cadena de texto, y el segundo("Hola Mundo"), le dice a la computadora la cadena de texto que queremos imprimir.

No te preocupes si no entendiste los términos, argumentos, función, cadena de texto o cualuier otro, los entenderás más adelante, sería imposible que te los explique ahora sin hacer que te pierdas más, solo ten paciencia.

[Ruta](https://astrodev07.github.io/Ruta.html)