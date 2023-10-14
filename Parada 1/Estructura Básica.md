# Estructura Básica de un Programa en C++
En C++, todos los programas tienen la misma estructura básica. En caso de que tu código no tenga esta estructura básica, pues no funcionará como lo esperas.

## ¿Cúal es esta estructura básica?
Pues bien, cada programa debe tener una función inicial llamada `main`, de esta forma:  
```cpp
int main(){
	// Tu código va aquí
	return 0;
}
```  
No obstante, aún así, hay otro factor muy importante para que tu programa funcione, incluir las librerías necesarias. Esto se debe hacer siempre antes de crear la función inicial, de esta forma:
```cpp
#include <iostream> // Librería  básica de C++
// Aquí puedes agregar otras librerías

int main(){
	// Tu código va aquí
	return 0;
}
```  
No te preocupes si aún no entiendes nada, solo debes entender por el momento que la estructura básica de un programa en C++ es esta:

```cpp
#include <iostream>

int main(){

	return 0;
}
```
Y tranquilo, en las siguientes lecciones entenderás mejor esta estructura.

[Ruta](../Ruta.html) | [Siguiente](Librerías.html)</div>