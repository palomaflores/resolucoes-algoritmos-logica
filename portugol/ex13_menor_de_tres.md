### Problema "menor_de_tres"
Fazer um programa para ler três números inteiros. Em seguida, mostrar qual o menor dentre os três números lidos. Em caso de empate, mostrar apenas uma vez. 

```portugol
Algoritmo "menor_de_tres"

Var
   x, y, z, menor: inteiro

Inicio
      escreva("Primeiro valor:")
      leia(x)
      escreva("Segundo valor:")
      leia(y)
      escreva("Terceiro valor:")
      leia(z)
      
      se (x < y) E (x < z) então
            menor <- x
            escreval("MENOR = ", x)
      senão
           se (y < z) então
              menor <- y
              escreval("MENOR = ", Y)
           senão (z < y) então
                 menor <- z
                 escreval("MENOR = ", z)
      fimse

Fimalgoritmo