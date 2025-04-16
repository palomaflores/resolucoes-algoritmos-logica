### Problema "operadora"
Uma operadora de telefonia cobra R$ 50.00 por um plano básico que dá direito a 100 minutos de telefone. Cada minuto que exceder a franquia de 100 minutos custa R$ 2.00. Fazer um programa para ler a quantidade de minutos que uma pessoa consumiu, daí mostrar o valor a ser pago. 

```portugol
Algoritmo "operadora"

Var
   min, tempoLimite, tempoExcedido : inteiro
   valorLimite, valorExtra, soma : real

Inicio
    escreva("Digite a quantidade de minutos: ")
    leia(min)
    

    tempoLimite <- 100
    tempoExcedido <- min - 100
    
    valorLimite <- 50.00
    valorExtra <- tempoExcedido * 2.00
    soma <- valorExtra + valorLimite
    
    se (min < 100) então
       escreval("Valor a pagar: R$ ", valorLimite:4:2)
    senão
         escreval("Valor a pagar: R$ ", soma:4:2)
    fimse
       

Fimalgoritmo