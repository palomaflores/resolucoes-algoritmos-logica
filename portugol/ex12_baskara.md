### Problema "baskara"
Fazer um programa para ler os três coeficientes de uma equação do segundo grau. Usando a fórmula de Baskara, calcular e mostrar os valores das raízes x1 e x2 da equação com quatro casas decimais,
conforme exemplo. Se a equação não possuir raízes reais, mostrar uma mensagem. 

```portugol
Algoritmo "notas"

Var
   a, b, c, x1, x2, denta : real

Inicio
   escreva("Coeficiente a:")
   leia(a)
   escreva("Coeficiente b:")
   leia(b)
   escreva("Coeficiente c:")
   leia(c)

   delta <- (b * b) - 4  * a * c

   x1 <- (-b + RaizQ(delta)) / 2 * a
   x2 <- (-b - RaizQ(delta)) / 2 * a
   
   se denta > 0 então
      escreval("X1 = ", x1:5:4)
      escreval("X1 = ", x1:5:4)
   senão
      escreval("Essa equação não possui raízes reais.")

Fimalgoritmo