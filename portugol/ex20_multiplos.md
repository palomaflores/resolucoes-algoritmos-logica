```
Algoritmo "multiplos"

Var
    x, y, resto: inteiro

Inicio

      escreva("Digite dois numeros inteiros:")
      leia(x, y)

      resto := x % y
      
      se (x % y = 0) ou (y % x = 0) entao
           escreval("Sao multiplos")
      senao
           escreval("Nao sao multiplos")
      fimse

Fimalgoritmo
```