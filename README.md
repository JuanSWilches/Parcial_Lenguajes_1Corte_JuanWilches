# Parcial_Lenguajes_1Corte_JuanWilches
# Punto_2
 1. Compila el Archivo LEX
Primero, asegúrate de que has compilado el archivo LEX (lambda_analyzer.l) para generar el ejecutable.

flex lambda_analyzer.l
gcc lex.yy.c -o lambda_analyzer -ll

2. Ejecuta el Programa.
3. 
para ejecutar el programa escribe en la terminal lambda_analyzer con el archivo de texto como argumento:

./lambda_analyzer archivo.txt

Este comando ejecutará el programa y procesará el contenido de archivo.txt, imprimiendo "ACEPTA" o "NO ACEPTA" para cada línea según las reglas definidas en el archivo LEX.


# Punto_3

Para compilar el programa, guarda el código en un archivo llamado, por ejemplo, miprograma.c, y luego usa gcc para compilarlo:

gcc -o miprograma miprograma.c

Para ejecutar el programa, usa:

./miprograma archivo.txt clave
Donde archivo.txt es el archivo de texto que quieres analizar y clave es la palabra clave que estás buscando.
