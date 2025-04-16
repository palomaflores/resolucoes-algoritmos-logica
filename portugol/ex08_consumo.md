### Problema "consumo"
Fazer um programa para ler a distância total (em km) percorrida por um carro, bem como o total de combustível gasto por este carro ao   percorrer tal distância. Seu programa deve mostrar o consumo médio do carro, com três casas decimais. 

```portugol
Algoritmo "consumo"

Var
   km : inteiro
   combustivelGasto, consumo : real

Inicio
      escreva("Distância total:")
      leia(km)
      
      escreva("Combustível gasto:")
      leia(combustivelGasto)
      
      consumo <- km/combustivelGasto
      escreval("Consumo médio = ", consumo:5:3)



Fimalgoritmo