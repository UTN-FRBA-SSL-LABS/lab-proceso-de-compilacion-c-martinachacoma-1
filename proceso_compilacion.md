Proceso de compilación – Lab 1 – Informe

Nombre: Martina Chacoma
Legajo: 222.211-5
Materia: Sintaxis y Semántica de Lenguajes
Docente: Christian Hernandez Weström

1. LINEAS_I=2247
2. LINEAS_O=8
3. El archivo programa.s se generó correctamente utilizando `gcc -S`.
   Contiene el código ensamblador del programa después de la fase de compilación.
4. Se generó el archivo ejecutable programa.exe utilizando:
   gcc programa.c matematica.c -o programa.exe

   El programa se ejecutó correctamente y produjo la siguiente salida:

   sumar(3, 4) = 7
   CUADRADO(5) = 25
   MAX(7, 12) = 12
   area_circulo(5.0) = 78.5398
   Factoriales:
     0! = 1
     1! = 1
     2! = 2
     3! = 6
     4! = 24
     5! = 120
   Llamadas a sumar(): 1
COMENTARIOS_EN_I=NO

R: Porque el preprocesador elimina los comentarios antes de la compilación.
