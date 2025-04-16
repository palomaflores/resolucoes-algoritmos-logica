### Problema "glicose"
Fazer um programa para ler a quantidade de glicose no sangue de uma pessoa e depois mostrar na tela a classificação desta glicose de acordo com a tabela de referência ao lado.

- NORMAL: Até 100 mg/dl
- ELEVADO: Maior que 100 até 140 mg/dl 
- DIABETES: Maior de 140 mg/dl

```portugol
Algoritmo "glicose"

Var
   glicose : real
   classificacao: caractere
   
Inicio
    escreva("Digite a medida da glicose:")
    leia(glicose)
    
    se (glicose < 100.0) então
       classificacao <- "normal"
    senão
         se (glicose >= 100.0) E (glicose <= 140.0) então
            classificacao <- "elevado"
         senão
              se(glicose >= 140.0) então
                classificacao <- "diabetes"
              fimse
         fimse
    fimse
    
    escreval("Classificacao: ", classificacao)

Fimalgoritmo