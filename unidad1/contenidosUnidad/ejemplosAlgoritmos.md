# 🔢Ejemplo de algoritmo con estructuras lineales/secuenciales
## Algoritmo para calcular aceleración

Para la elaboración de este algoritmo, primero se definieron las variables a utilizar, asignándoles su tipo de dato correspondiente.
Posteriormente, se establecieron los datos de entrada y salida, y se programó la lectura de los valores ingresados por el usuario.
En PSeInt se emplea la instrucción **Leer**, mientras que en el lenguaje C se utiliza **scanf**.

Una vez ingresados los datos, se procede con el proceso de cálculo, aplicando la fórmula para determinar la aceleración.
Finalmente, el resultado obtenido se muestra en pantalla mediante la instrucción **Escribir** en PSeInt o **printf** en C.

Este tipo de algoritmos lineales permite comprender cómo se ejecutan las instrucciones en orden secuencial, sin saltos, lo que facilita el análisis y la depuración de errores.

<details>
  <summary><b>💡 Ver código de PSeInt</b></summary>

    
  ```pseudocode
    Algoritmo aceleracion1
    	//Variables
    	Definir vIncial, vFinal, tiempo, aceleracion Como Real;
    
    	//Entrada
    	Escribir "Ingrese la velocidad inicial en (m/s): ";
    	Leer vIncial;
    	Escribir "Ingrese la velocidad final en (m/s): ";
    	Leer vFinal;
    	Escribir "Ingrese el tiempo en (s): ";
    	Leer tiempo;
    	
    	//Proceso 
    	aceleracion = (vFinal - vIncial) / tiempo;
    	
    	//Salida
    	Escribir "La aceleracion es: ",aceleracion " m/s^2";
    FinAlgoritmo
  ```
</details>



<details>
<summary><b>💡 Ver diagrama de flujo</b></summary>
  <img src="/img/diagramaFlujo.png" alt="Diagrama de flujo" width="200">
</details>


  
<details>
  <summary><b>💡 Ver código en C</b></summary>

<br>

```c
    #include <stdio.h>
    
    int main(){
        float vInicial, vFinal, tiempo, aceleracion;
        printf("Ingrese la velocidad inicial en (m/s): ");
        scanf("%f", &vInicial);
        printf("Ingrese la velocidad final en (m/s): ");
        scanf("%f", &vFinal);
        printf("Ingrese el tiempo en (s): ");
        scanf("%f", &tiempo);
    
        aceleracion = (vFinal - vInicial) / tiempo;
        
        printf("La aceleracion es: %.2f m/s^2", aceleracion);
    }
```

</details>

➡️ [**Ir a página siguiente**](/unidad1/contenidosUnidad/dificulatdes.md)

➡️ [**Ir al índice**](/index.md)
