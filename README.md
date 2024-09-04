# Parcial_Lenguajes_1Corte_JuanWilches
# Punto_2
 1. Compila el Archivo LEX
Primero, asegúrate de que has compilado el archivo LEX (lambda_analyzer.l) para generar el ejecutable.

flex lambda_analyzer.l
gcc lex.yy.c -o lambda_analyzer -ll

2. Ejecuta el Programa
para ejecutar el programa escribe en la terminal lambda_analyzer con el archivo de texto como argumento:

./lambda_analyzer archivo.txt

Este comando ejecutará el programa y procesará el contenido de archivo.txt, imprimiendo "ACEPTA" o "NO ACEPTA" para cada línea según las reglas definidas en el archivo LEX.
