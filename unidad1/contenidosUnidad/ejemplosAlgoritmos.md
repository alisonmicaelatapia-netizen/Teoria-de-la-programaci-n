# 🔢Ejemplo de algoritmo con estructuras lineales/secuenciales
## Algoritmo para calcular aceleración
<details>
  <summary><b>💡 Ver código de PSeInt</b></summary>

    
    ```
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
