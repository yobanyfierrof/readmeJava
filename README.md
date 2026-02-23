# readmeJava
Ejercicio 1: Imprimir números del 1 al 20, pares del 1 al 50 y conteo descendente del 20 al 1.
Explicación: En este primer ejercicio realizamos un conteo del 1 hasta el 20, para ello utilizamos un ciclo for, con los tres pasos elementales, 1) creamos la variable int i = 1 donde el int es para inicializar la variable, 2) la condición que se va a cumplir i = 20 en este caso ese es el límite de los números, 3) i++ es para que haya un incremento de i. y por último el sout para imprimir en pantalla i.

Explicación: En este ejercicio vamos a hacer que el programa seleccione los números pares del 1 al 50, para realizarlo utilizamos un ciclo for con los tres elementos básicos, utilizamos un condicional if para que se cumpla esa condición de que todo número divisible por dos y el residuo sea cero, ese es un número par.

Explicación: En el  presente ejercicio realizamos una cuenta regresiva desde 20  hasta 1. Utilizamos un ciclo for en el cual se dieron las indicaciones de la siguiente manera: i=20 esto indica que i se inicializa desde 20, i >= 1 aquí indicamos que el conteo llega hasta uno, y el i—es para que el programa inicie un decremento.

Ejercicio #2 Crear arreglo de 10 enteros y calcular suma, promedio y número mayor usando for.
Salida en pantalla
Explicación del ejercicio: 
•	Declaramos un arreglo llamado numero con diez valores enteros definidos.
•	Se crea la variable suma la cual inicia en cero (0) para acumular valores; la variable mayor se inicializa con el primer número del arreglo.
•	Usamos el ciclo for para recorrer el arreglo números.length para la cantidad total de elementos.
•	Calculamos la suma así: suma += números[i];
•	Para calcular el número mayor, comparamos cada número con la variable mayor utilizando el condicional if 
•	Para calcular el promedio, se divide la suma de los enteros entre la cantidad de elementos del arreglo.
•	Se imprime la suma de todos los enteros que están en el arreglo, luego el promedio y después el número mayor.

Ejercicio 3: Imprimir patrón numérico incremental usando for anidado.
Explicación:
•	En el primer for podemos evidenciar que es para controlar el número de filas que tendrá el patrón, este es el for incremental
•	El segundo for es un ciclo interno, el cual depende de i, imprime números desde 1 hasta el valor de la fila, en este caso hasta 5.
•	El sout utilizado debajo del segundo for, es un salto de línea después de cada fila.
•	El funcionamiento, es cuando el ciclo interno se ejecuta cada vez que el ciclo externo avanza una fila.

Ejercicio 4: Crear matriz 3x3, llenarla con números del 1 al 9 y mostrarla en formato tabla
Explicación:
•	Se declara la matriz de 3 x 3 la cual contendrá 3 filas y 3 columnas. 
•	Se crea una variable llamada numero la cual la iniciamos en 1.
•	Se procede a llenar la matriz con los números del 1 al 9 con ciclos  for anidados, donde el primer for recorre las filas, el segundo for recorre las columnas. En cada posición se guarda el valor de número y luego se incrementa. 
•	Ahora para mostrar la matriz en formato de tabla, utilizamos de nuevo ciclos for para imprimir los valores, utilizamos \t para dar formato de tabla.

Ejercicio 5: Crear matriz 4x4, mostrarla, calcular suma por filas y suma total usando for anidado.
Explicación:
•	Procedemos a crear la matriz 4x4, cuatro filas con cuatro números cada una {….}.
•	Creamos una variable llamada sumaTotal y la iniciamos con cero (0).
•	Ahora utilizamos dos ciclos for para recorrer la matriz, el primer for recorre las filas y el segundo for las columnas.
•	Ahora vamos a calcular la suma total por cada fila, al terminar cada fila se suma sumaFila += sumaTotal.

•	Luego se imprime el total de la matriz y me muestra un valor el cual corresponde a la suma del total de cada fila.
