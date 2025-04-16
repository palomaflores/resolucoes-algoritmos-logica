### Problema "troco"
Fazer um programa para calcular o troco no processo de pagamento de um produto de uma mercearia.
O programa deve ler o preço unitário do produto, a quantidade de unidades compradas deste produto, e o valor em dinheiro dado pelo cliente (suponha que haja dinheiro suficiente). Seu programa deve
mostrar o valor do troco a ser devolvido ao cliente. 


```portugol
Algoritmo "troco"

Var
   precoUnit, pagamento, troco, total: real
   quant : inteiro

Inicio
   escreva("Preço unitário do produto:")
   leia(precoUnit)
   
   escreva("Quantidade comprada:")
   leia(quant)
   
   escreva("Dinheiro recebido:")
   leia(pagamento)
   
   total <- quant * precoUnit
   troco <- pagamento - total
   
   escreval("TROCO = ", troco:2:2)


Fimalgoritmo