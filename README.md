# algoritmos-peseint-lab-fernanda
información del estudiante 
Nombre: María Fernanda Martínez Picado 
sección:grupo#4
"Colección de algoritmos de la clase"
Proceso Promedio
    definir i, n como entero
    definir acum, dato, prom como real
    escribir "Ingrese la cantidad de datos:"
    leer n
    acum <- 0
    para i <- 1 hasta n hacer
        escribir "Ingrese el dato ", i, ":"
        leer dato
        acum <- acum + dato
    finpara
    prom <- acum / n
    escribir "El promedio es: ", prom
FinProceso
