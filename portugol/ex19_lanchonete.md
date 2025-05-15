```portugol
Algoritmo "lanchonete"

Var
    x, y : inteiro
    preco : real
     
Inicio

      escreva("Codigo do produto comprado:")
      leia(x)
      escreva("Quantidade comprada:")
      leia(y)
      
      se (x=1) entao
         preco <- y * 5.00
         escreva("Valor a pagar: R$ ", preco:5:2)
      senao
           se (x=2) entao
              preco <- y * 3.50
              escreva("Valor a pagar: R$ ", preco:5:2)
           senao
                se (x=3) entao
                   preco <- y * 4.80
                   escreva("Valor a pagar: R$ ", preco:5:2)
                senao
                     se (x=4) entao
                        preco <- y * 8.90
                        escreva("Valor a pagar: R$ ", preco:5:2)
                     senao
                          se (x=5) entao
                             preco <- y * 7.32
                             escreva("Valor a pagar: R$ ", preco:5:2)
                          fimse
                     fimse
                fimse
           fimse
      fimse

Fimalgoritmo
```