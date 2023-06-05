# Suma de Riemann

## Estudiante
- Luis Aaron Nieto Cruz ([LuisAaronNietoCruz](https://github.com/LuisAaronNietoCruz))

## Objetivo
El objetivo del programa es calcular la integral (Riemann) de una función en un intervalo dado utilizando múltiples procesos en un entorno de programación paralela con MPI (Message Passing Interface).

## Ejecución
Clonar el repositorio:
git clone https://github.com/LuisAaronNietoCruz/Practica_Suma_de_Riemann.git

Compilar el archivo main:
`mpicc main.c -o main`

Correr el archivo compilado:
`mpiexec -n [numero de procesos] ./main [a] [b] [range] [n]`

## Resultado

Con:

a = 0. # donde `a` es el límite inferior del intervalo de integración.

b = 2. # donde `b` es el límite superior del intervalo de integración.

range = 10. # donde `range` es el número de segmentos en que se divide el intervalo de integración.

n = 5000. # donde `n` es el número de particiones de cada segmento.

Número de procesos = 8.

![image](https://github.com/LuisAaronNietoCruz/Practica_Suma_de_Riemann/blob/main/Compilaci%C3%B3n_main.c.jpg)
