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
`mpiexec -n 8 ./main 0 2 10 5000`

## Resultado

Con:

a = 0

b = 2

= 10

= 5000

Utilizando 8 procesadores.

![image](https://github.com/LuisAaronNietoCruz/Practica_Suma_de_Riemann/assets/100148692/2b481ae5-eea7-4563-8830-fbced7bf7521)
