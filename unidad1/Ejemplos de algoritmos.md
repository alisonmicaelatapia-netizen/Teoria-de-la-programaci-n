# Ejemplos de algoritmos con estructuras lineales/secuenciales

Algoritmo cambioDinero
    # Variables
    Definir dineroActual Como Real;
    Definir precioProducto Como Real;
    Definir cambio Como Real;
    
    # Entrada
    Escribir "Ingrese el dinero que dispone: ";
    Leer dineroActual;
    Escribir "Ingrese el precio del producto: ";
    Leer precioProducto;
    
    # Proceso 
    cambio = dineroActual - precioProducto;
    
    # Salida
    Escribir "Su cambio es: $", cambio;
FinAlgoritmo
