# Código
```md
algoritmo "exercicio4-repeticao"
var
    totalCaixas, pesoTotal, pesoCaixa: Real
    maxCaixas, maxPeso: Inteiro
inicio
maxCaixas <- 200
maxPeso <- 10000

totalCaixas <- 0
pesoTotal <- 0

Enquanto (totalCaixas < maxCaixas E pesoTotal < maxPeso) faça
    Escreva "Digite o peso da caixa (kg): "
    Leia pesoCaixa

    Se (pesoTotal + pesoCaixa > maxPeso) então
        Escreva "Não é possível adicionar esta caixa. Limite de peso excedido."
        Saia do loop
    FimSe

    totalCaixas <- totalCaixas + 1
    pesoTotal <- pesoTotal + pesoCaixa
FimEnquanto

Se totalCaixas > 0 então
    pesoMedio <- pesoTotal / totalCaixas
    Escreva "Quantidade de volumes: ", totalCaixas
    Escreva "Peso total dos volumes: ", pesoTotal
    Escreva "Peso médio dos volumes: ", pesoMedio
Senao
    Escreva "Nenhuma caixa foi adicionada."
FimSe
fimalgoritmo

```