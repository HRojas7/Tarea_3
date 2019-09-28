# Tarea_3
Tarea NÂ° 3 Big Data

Ejercicio 1: 

#Al reemplazar en listaDeNumeros[5] el 5 por un 0, la respuesta que da es list().
#Al colocar en listaDeNumeros[] un número mayor al total de números en la lista que son 11, la respuesta que da es 
[[1]] 
NULL

Ejercicio 2:

#Al utilizar la función unlist(listaDeNumeros[5]), la diferencia se ve en la respuesta que da:
[1] 1

#a diferencia de antes que era:
[[1]]
[1] 1

#Al utilizar la función if, con la función unlist y sin ella, me da el mismo resultado.
#Podria servir unlist para entregar un valor más preciso de lo que se esta buscando, más directo.
#Al agregar la suma en la funcion if sin unlist, arroja el siguiente error:
Error in (listaDeNumeros[9]) + 5 : 
  non-numeric argument to binary operator
  
#en cambio al agregar la suma en la funcion if con unlist, arroja el resultado sin ningún problema.

Ejercicio 3:

#Al ejecutar listaDeNumeros[5] <- 12 abajo se repite nuevamente listaDeNumeros[5]

Ejercicio 4:

#Debe ser cambiado porel nombre de la variable que es listaDeNumeros, y al ejecutar da como resultado:
[1] 11
> listaDeNumeros[5]

Ejercicio 5:

#dando el 5 al valor inicial y el 11 al valor final, cuando se ejecuta la respuesta muestra los números desde el 5 hasta el 11 de la siguiente manera:
>valorInicial: valorFinal
[1] 5 6 7 8 9 10 11

#Al asignar el 11 al valor inicial y el 5 al valor final, cuando se ejecuta la respuesta muestra nuevamente los números desde el 5 hasta el 11 pero en orden descendente de la siguiente manera:
>valorInicial: valorFinal
[1] 11 10 9 8 7 6 5

#Al utilizar el length nos muestra la secuencia de números desde o hasta el número de elementos de la variable, hasta o desde el número que escojamos, de esta manera:
> length(listaDeNumeros):8
[1] 11 10  9  8

> 8:length(listaDeNumeros)
[1]  8  9 10 11

Ejercicio 6:

#La condición es dar a i el valor de una lista del 1 al 100

Ejercicio 7:

#Al adaptar el código para que se ejecute con la lista de números creada, se repite la palabra "cuento" y "misisipis", con la diferencia que esta vez en medio ocupa los números de la lista que se creo y solamente se repite 11 que es el número de valores que tiene la lista.

Ejercicio 8:

#
