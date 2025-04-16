### Problema "troco_verificado"
Fazer um programa para calcular o troco no processo de pagamento de um produto de uma mercearia.
O programa deve ler o preço unitário do produto, a quantidade de unidades compradas deste produto, e o valor em dinheiro dado pelo cliente. Seu programa deve mostrar o valor do troco a ser devolvido
ao cliente. Se o dinheiro dado pelo cliente não for suficiente, mostrar uma mensagem informando o valor restante conforme exemplo. 

```portugol

Algoritmo "troco_verificado"

Var
     quant : inteiro
     precoUnit, pagamento, total, troco : real

Inicio
      escreva("Preço unitário do produto: ")
      leia(precoUnit)
      escreva("Quantidade comprada: ")
      leia(quant)
      escreval("Dinheiro recebido: ")
      leia(pagamento)
      
      total <- precoUnit * quant
      troco <- pagamento - total
      
      se (pagamento > total) então
         escreval("TROCO = ", troco:4:2)
      senão (pagamento < total) então
            escreval("DINHEIRO INSUFICIENTE. FALTAM, ", -troco:4:2," REAIS.")
      fimse


Fimalgoritmo