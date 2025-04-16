### Problema "medidas"
Fazer um programa para ler três medidas A, B e C. Em seguida, calcular e mostrar (imprimir os dados com quatro casas decimais):
 - a área do quadrado que tem lado A
 - a área do triângulo retângulo que base A e altura B
 - a área do trapézio que tem bases A e B, e altura C 

```portugol
Algoritmo "medidas"

Var
    A, B, C, areaQuad, areaTri, areaTrap : real

Inicio
    escreva("Digite a medida A:")
    leia(A)
    escreva("Digite a medida B:")
    leia(B)
    escreva("Digite a medida C:")
    leia(C)
    
    areaQuad <- A * A
    areaTri <- (A * B)/2
    areaTrap <- ((A + B) * C)/2
    
    escreval("AREA DO QUADRADO = ", areaQuad:6:4)
    escreval("AREA DO TRIANGULO = ", areaTri:6:4)
    escreval("AREA DO TRAPEZIO = ", areaTrap:6:4)
    


Fimalgoritmo
