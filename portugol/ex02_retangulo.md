### Problema "retangulo"
Fazer um programa para ler as medidas da base e altura de um retângulo. Em seguida, mostrar o valor da área, perímetro e diagonal deste retângulo, com quatro casas decimais, conforme exemplos. 


```portugol
Algoritmo "retangulo"

Var
   base, altura, perimetro, area, diagonal : real

Inicio
    escreva("Base do retangulo:")
    leia(base)
    escreva("Altura do retangulo:")
    leia(altura)
    
    area <- base * altura
    perimetro <- (2*(base + altura))
    diagonal <- RaizQ((base*base) + (altura*altura))
    
    escreval("AREA = ", area:6:4)
    escreval("PERIMETRO = ", perimetro:6:4)
    escreval("DIAGONAL = ", diagonal:5:4)

Fimalgoritmo