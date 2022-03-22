# REALIZA LOS SIGUIENTES EJERCICIOS

Realizar un algoritmo y diagrama de flujo para un programa que permita ingresar un nombre y una cantidad numérica para que así después el programa escriba este nombre tantas veces como su cantidad ingresada.

  1. Inicio
  2. Declarar (nombre, contador, numero) int
  5. Mostrar ("Ingresar Numero")
  6. Asignar (numero)
  7. Mostrar ("Ingresar nombre")
  8. Asignar (nombre)
  9. Asignar (contador=1)
  10. PARA (contador <= numero) mostrar (nombre) contador = contador + 1 FIN PARA
  11. FIN

![image](https://user-images.githubusercontent.com/85717673/159536301-a085bb8f-09d3-45cd-bf46-5df894bd5254.png)

    var nombre;
    var contador;
    var numero;
    numero = prompt("Ingresar numero")
    nombre = prompt("Ingresar nombre")
    for(contador = 1;contador <= numero;contador++){
    document.write(nombre + "<br>")
    }

Realizar algoritmo y diagrama de flujo de un programa que imprima las tablas de multiplicar del 1 al 10.

  1. Inicio
  2. Decalarar (contador1, contador2, resultado) int
  3. Asingar (contador1 = 1)
  4. Asignar (contador2 = 1)
  5. PARA (contador1 <= 10) && (contador2 <= 10) resultado = contador1 * contador2 mostrar(contador1 * contador2 = resultado) contador1 = contador1 + 1 contador2 = contador2 + 1 PARA FIN
  6. FIN



