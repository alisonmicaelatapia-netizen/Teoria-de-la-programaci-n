# 🔄 Ejercicio combinando estructura condicional y repetitiva
## **Descripción del problema:** 
Un programa debe registrar las compras de varios clientes durante el día.<br>
El registro se repetirá hasta que se ingrese un monto igual a 0. <br>
En cada repetición se debe ingresar solo el monto de la compra. <br>
El programa debe cumplir lo siguiente: <br> 
  1. Si el monto es mayor a 50, se aplica un descuento del 10%. <br>
  2. Si el monto es 50 o menor, no hay descuento. <br>
  3. El programa debe mostrar el monto final a pagar por cada compra. <br>
  
  Al finalizar (cuando se ingrese 0), el programa debe mostrar: <br>
*El total de compras registradas. <br>
*El total de dinero recaudado.<br>

<details>
<summary><b>💡 Ver diagrama de flujo</b></summary>
  <img src="/img/registroCompras.png" alt="Diagrama de flujo" width="550">
</details>

<details>
  <summary><b>💡 Ver código en Python</b></summary>

<br>

```py
    monto = 1
    contador = 0
    total = 0
    
    while(monto != 0):
        monto = int(input("Ingrese su monto de compra: "))
        if (monto > 50):
            descuento = monto * 0.1
            total = total + (monto - descuento)
        else:
            total = total + monto
    
        print(f"El monto a pagar es: $", total)
        contador += 1
    
    print(f"El total de compras registradas:", contador - 1)
    print(f"El total de dinero recaudado es: $", total)

```
</details>

<details>
<summary><b>💡 Ver verificación</b></summary>
  <strong>Pruebas de escritorio</strong><br>
  *Prueba 1 <br>
  <img src="/img/prueba-1.png" alt="Prueba 1" width="400"><br>
  *Prueba 2 <br>
  <img src="/img/prueba-2.png" alt="Prueba 2" width="400"><br>
  *Prueba 3 <br>
  <img src="/img/prueba-3.png" alt="Prueba 3" width="400"><br>
</details>


➡️ [**Ir a página siguiente**](/unidad2/contenidosUnidad/dificultades.md)

➡️ [**Ir al índice**](/index.md)
