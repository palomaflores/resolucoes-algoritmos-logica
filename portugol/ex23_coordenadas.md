```portugol
Algoritmo "coordenadas"

Var

   x , y: real

Inicio

      escreva("Valor de X:")
      leia(x)
      escreva("Leia valor de Y:")
      leia(y)

se (x > 0)  e  (y > 0) entao
    escreval("Q1")
senao
    se (x < 0)  e  (y > 0) entao
        escreval("Q2")
    senao
        se (x < 0)  e  (y < 0) entao
            escreval("Q3")
        senao
            se (x > 0)  e  (y < 0) entao
                escreval("Q4")
            senao
                se (x > 0)  e  (y = 0) entao
                    escreval("Eixo X")
                senao
                    se (x = 0)  e  (y > 0) entao
                        escreval("Eixo Y")
                    senao
                         se (x = 0)  e  (y = 0) entao
                            escreval("Origem")
                        fimse
                    fimse
                fimse
            fimse
        fimse
    fimse
fimse

Fimalgoritmo
```portugol