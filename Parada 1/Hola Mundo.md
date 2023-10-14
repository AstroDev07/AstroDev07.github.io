# Hola Mundo
A partir de esta nueva lección, comenzaremos a crear crear códigos que de alguna manera sean "Funcionales". Con esto me refiero a que nuestros programas a partir de aquí, realizarán alguna que otra tarea sencilla y, poco a poco, irán aumentando su dificultad.

## ¿Con qué empezaremos?
Ahora, crearemos un *Hola Mundo*, que es el ejemplo que se usa comunmente para desarrollar tu primer programa en cualuier lenguaje. Pero, dejemonos de charla y vamos a chambear...
```cpp
#include <iostream>

int main(){
	std::cout<<"Hola Mundo";
	return 0;
}
```
Así es, esto escribe Hola Mundo en la pantalla. No te asustes, la primera vez que lo hice, yo tampoco entendí nada, pero yo te lo explicaré ahora mismo.

## Explicación
Para empezar, creamos la estructura básica del programa que ya estudiamos en lecciones anteriores, declaramos las librerías a usar, creamos la función inicial `main`, y, dentro de ella, agregamos nuestro código.

En este caso, la linea 4, es la encargada de escribir en la pantalla lo que queremos, así que vamos a analizarla.
```cpp
std::cout<<"Hola Mundo";
```
Primero, analizemos la parte `std::`, esto es lo que se llama `namespace` en español espacio de nombre pero ignora el español. Básicamente lo que hace es avisar a la computadora de que estamos utilizando un función de la librería `iostream`. Sí, std es el `namespace` correspondiente a la librería `iostream`.

Y `cout<<` es la función que se esta usando, esta función es la encargada de imprimir texto en la pantalla. Tiene una explicación más profunda, pero por eso mismo la dejaremos de utilizar por un buen tiempo. ¿Que cúal usaremos? tranquilo, lo veremos más adelante y sabrás por que.

[Ruta](https://astrodev07.github.io/Ruta.html)