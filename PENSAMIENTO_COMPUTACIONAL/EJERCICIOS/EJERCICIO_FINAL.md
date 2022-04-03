Realiza en algoritmo, pseudocodigo y diagrama de flujo, un Juego simple que pide al usuario que adivine un numero en 10 intentos, que imprima si lo atina, y si no le indique si el número ingresado es mayo o menor al almacenado, así como el número de intemtos restantes.

    Algoritmo adivina_el_numero
    intentos<-5
    num_secreto <- 56
    Escribir "Adivine el numero:"
    Leer num_ingresado
    Mientras num_secreto<>num_ingresado && intentos>1 Hacer
        Si num_secreto>num_ingresado Entonces
            Escribir "Muy bajo"
        Sino 
            Escribir "Muy alto"
        FinSi
        intentos <- intentos-1
        Escribir "Le quedan ",intentos," intentos:"
        Leer num_ingresado
    FinMientras
    Si num_secreto=num_ingresado Entonces
        Escribir "Exacto! Usted adivino en ",intentos," intentos."
    Sino
        Escribir "El numero era: ",num_secreto
    FinSi
FinAlgoritmo

Ingresa al siguiente link para el resumen final

https://docs.google.com/presentation/d/17LildSvlBpnu-FRpMW1ITRiO21_f3Z0cF9q1Zrs6K5U/edit?usp=sharing
