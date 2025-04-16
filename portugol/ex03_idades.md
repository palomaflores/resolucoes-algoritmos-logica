### Problema "idades"
Fazer um programa para ler o nome e idade de duas pessoas. Ao final mostrar uma mensagem com os nomes e a idade média entre essas pessoas, com uma casa decimal, conforme exemplo. 


```portugol
Algoritmo "idades"

Var
   nome1, nome2 : caractere
   idade1, idade2 : inteiro
   idadeMedia : real

Inicio
   escreval("DADOS DA PRIMEIRA PESSOA")
   escreva("Nome:")
   leia(nome1)
   escreva("Idade:")
   leia(idade1)
   
   escreval("DADOS DA SEGUNDA PESSOA")
   escreva("Nome:")
   leia(nome2)
   escreval("Idade:")
   leia(idade2)
   
   idadeMedia <- (idade1 + idade2)/2
   
   escreval("A idade média de ",nome1," e ",nome2," é de ", idadeMedia," anos.")


Fimalgoritmo
