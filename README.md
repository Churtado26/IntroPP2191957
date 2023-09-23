# InttroPP2191957

----------///----------///----------///---TALLER 1---///----------///----------///----------///

El archivo analizado lleva por nombre "mulma.c", en el cual se realiza un ejercicio de multiplicacion de matrices en paralelo y en secuencial, para analizar los resultados de tiempo obtenidos.
# Ejecución

Para ejecutar el codigo en guane, es necesario crear un archivo de texto, para este caso utilizaremos vim, con el siguiente comando:

    vim mulma.c

Despues se pega el codigo que ejcuta la operacion y se guarda el archivo dando esc y escribiendo :wq!

Posteriormente se ejecuta el siguiente comando:

    gcc -std=c99 -Wall -fopenmp mulma.c -o mulma

Este nos permite utilizar el compilador de c y nos pueda mostrar el registro de errores (En caso de haberlos), además de crear el archivo ejecutable

Para correr el ejecutable anteriormente creado se corre el siguiente comando:

    ./mulma

Con esto se puede ver el resultado de la ejecucion de el codigo de multiplicacion de matrices.
El proceso de ejecución del código paralelizado es el mismo, simplemente es cambiar el nombre del archivo por "omp_ulma"

Para el inciso de alterar el tamaño de las matrices, se debe modificar en el codigo en el editor de texto vim
