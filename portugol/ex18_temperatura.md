```portugol
Algoritmo "temperatura"

Var
     C, F : real
     x : caractere
     
Inicio
    escreva("Voce vai digitar a temperatura em qual escala (C/F)?")
    leia(x)
    
    se (x = "C") entao
       escreva("Digite a temperatura em Fahrenheit:")
       leia(F)
       
       C := 5/9 * (F-32)
       
       escreva("Temperatura equivalente em Celsius:", C:5:2)
    senao
      se (x = "F") entao
        escreva("Digite a temperatura em Celsius:")
        leia(C)
        
        F := (1.8 * C) + 32
        
        escreva("Temperatura equivalente em Fahrenheit:", F:5:2)
      fimse
    fimse

Fimalgoritmo
```