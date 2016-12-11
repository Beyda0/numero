var rango = 0 ... 100
for numero in rango {
    if numero % 5 == 0{
        print ("\(numero) Bingo!!!")
    }
    else if numero % 2 == 0{
        print ("\(numero) par!!!")
    }
    else if numero % 1 == 0 {
        print ("\(numero) impar!!!")
    }
    if numero >= 30 && numero <= 40{
        print ("\(numero) Viva Swift!!!")
    }
}

