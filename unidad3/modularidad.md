# CONTENIDOS DE LA UNIDAD
# 🔀 Modularidad
Es un paradigma de la programación que se basa en la división de un sistema en partes más pequeñas, funcionales e independientes, conocidas como módulos. Cada módulo cumple una función específica y puede desarrollarse, analizarse y probarse de manera separada, lo que facilita la organización y comprensión del sistema en su conjunto[5]. Este enfoque resulta especialmente útil cuando se trabaja con algoritmos largos y complejos, ya que permite reducir la complejidad, mejorar la reutilización del código, simplificar el mantenimiento y favorecer la detección de errores, al mismo tiempo que se garantiza una interacción ordenada entre los distintos módulos que conforman el programa.

## Funciones

Las funciones son bloques de código diseñados para realizar una tarea específica dentro de un programa. Permiten encapsular un conjunto de instrucciones que se ejecutan cuando la función es llamada, pudiendo recibir datos de entrada llamados parámetros y devolver un resultado. El uso de funciones facilita la organización del código, promueve la reutilización, reduce la redundancia y mejora la legibilidad y el mantenimiento de los programas.

**Sintaxis en c:**
```C
    tipo_de_retorno nombre_de_la_funcion(tipo_parametro parametro1, tipo_parametro parametro2) {
    // Cuerpo de la función
    // Instrucciones a ejecutar

    return valor; // Solo si el tipo de retorno no es void
}

```
* **Pase de parámetros por valor:**
  Se envía el contenido de la variable a la función que lo utilizara en sus instrucciones, pero la variable original no se altera.

  ![Parametros por valor](/img/parametroValor.png) <br>

  
  > Ejemplo 1: Se intenta intercambiar los valores de a y b, pero al pasarlos por valor la función solo modifica copias, por lo que los valores originales no cambian.
  
* **Pase de parámetros por referencia:**
    Se envía la dirección de memoria de la variable es decir si dentro de la función se realiza algún cambio pues la variable fuera de la     función sufrirá este cambio.

  ![Parametros por valor](/img/parametroReferencia.png) <br>

  
  > Ejemplo 2: En este ejercicio se realiza el intercambio de los valores de a y b mediante paso de parámetros por referencia, lo que permite modificar directamente las variables originales.
</details>

