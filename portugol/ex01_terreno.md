### Problema "terreno"
Fazer um programa para ler as medidas da largura e comprimento de um terreno retangular com uma casa decimal, bem como o valor do metro quadrado do terreno com duas casas decimais. Em seguida, o programa deve mostrar o valor da área do terreno, bem como o valor do preço do terreno, ambos com duas casas decimais, conforme exemplo. 

```portugol
Algoritmo "terreno"

Var
   larg, comp, Mquadrado, area, preco : real


Inicio
   escreva("Digite a largura do terreno:")
   leia(larg)
   escreva("Digite o comprimento do terreno:")
   leia(comp)
   escreva("Dgite o valor do metro quadrado:")
   leia(Mquadrado)
   
   area <- larg * comp
   escreval("Area do terreno = ", area)
   
   preco <- area * Mquadrado
   escreval("Preco do terreno = ", preco)


Fimalgoritmo