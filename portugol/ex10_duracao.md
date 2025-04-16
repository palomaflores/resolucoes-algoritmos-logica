### Problema "duracao"
Fazer um programa para ler uma duração de tempo em segundos, daí imprimir na tela esta duração no formato horas:minutos:segundos. 

```portugol
lgoritmo "duracao"

Var
    hora, minutos, segundos, duracao, resto: real

Inicio
    escreva("Digite a duracao em segundos:")
    leia(duracao)
    
    hora <- duracao/3600
    resto <- duracao % 3600
    minutos <- resto/60
    segundos <- resto % 60

   escreva(hora:2,":",minutos:2,":",segundos:2)

Fimalgoritmo