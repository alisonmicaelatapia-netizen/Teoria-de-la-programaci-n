# 🔁 Arreglos
Es una estructura de datos que permite almacenar un conjunto de elementos del mismo tipo bajo un único nombre, organizados en posiciones consecutivas de memoria y accesibles mediante un índice. Esta organización facilita el acceso directo a cada elemento, lo que mejora la eficiencia en la manipulación de datos [5]. Los arrays se utilizan comúnmente para gestionar colecciones de información, como listas de números o registros, y pueden ser de tamaño fijo o, según el lenguaje de programación, dinámico, lo que los convierte en una herramienta fundamental en el desarrollo de algoritmos y aplicaciones.
* **Unidimensional:**
Es una estructura de datos que almacena elementos del mismo tipo en una sola lista, a los que se accede mediante   un único índice.
``` C
  //Unidimensional
  //Columnas
  int numeros[5] = {1, 2, 3, 4, 5};

  //Acceso a elementos sintaxis
  array[i]

```
* **Bidimensional:**
  Es una estructura de datos que organiza la información en filas y columnas, similar a una tabla o matriz, y permite acceder a cada elemento mediante dos índices que representan su posición.
``` C
  //Filas - columnas
  int matriz[2][3] = {
  {1, 2, 3},
  {4, 5, 6}
};

 //Acceso a elementos sintaxis
  array[fila][columna]
```

* **Tridimensional:**
  Almacena datos en tres dimensiones, lo que permite representar información más compleja, como volúmenes o conjuntos de matrices, accediendo a cada elemento mediante tres índices.
``` C
  //Capa - Filas - Columnas
  int cubo[2][2][2] = {
  { {1, 2}, {3, 4} },
  { {5, 6}, {7, 8} }
};

//Acceso a elementos sintaxis
  array[capa][fila][columna]
```
➡️ [**Ir a página siguiente**](/unidad3/dificultades.md) 

➡️ [**Ir al índice**](/index.md)
