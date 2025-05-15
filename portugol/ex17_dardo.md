```portugol
Algoritmo "dardo"

Var
  distancia1, distancia2, distancia3, maior : real

Inicio
  escreva("Digite as tres distancias:")
  leia(distancia1, distancia2, distancia3)


  se (distancia1 > distancia2) e (distancia1 > distancia3) entao
     maior <- distancia1
  senao
       se (distancia2 > distancia1) e (distancia2 > distancia3) entao
          maior <- distancia2
       senao (distancia3 > distancia1) e (distancia3 > distancia2) entao
          maior <- distancia3
       fimse
  fimse
  
  escreval("MAIOR DISTANCIA = ", maior)


Fimalgoritmo
```