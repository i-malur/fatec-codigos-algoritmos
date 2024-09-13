# Exercício 7A
```md
algoritmo "exercicio07A-manzano"
var
   C, F: real

inicio

   escreval("Digite a temperatura em graus Celsius: ")
   leia(C)
   F := (9 * C + 160) / 5
   escreval("A temperatura em graus Fahrenheit é: ", F)

fimalgoritmo
```

# Exercício 7B
```md
algoritmo "exercicio07B-manzano"
var
   C, F: real

inicio

   escreval("Digite a temperatura em graus Fahrenheit: ")
   leia(F)
   C := (F - 32) * (5/9)
   escreval("A temperatura em graus Celsius é: ", C)

fimalgoritmo
```

# Exercício 7C
```md
algoritmo "exercicio07C-manzano"
var
   altura, raio, p, volume: real

inicio

   p := 3.14
   escreval("Digite a altura da lata: ")
   leia(altura)
   escreval("Digite o raio da lata: ")
   leia(raio)
   volume := p * altura * (raio*raio)
   escreval("O resultado do volume da lata de óleo ", volume)

fimalgoritmo
```

# Exercício 7D
```md
Algoritmo "exercicio07D-manzano"

Var
   TEMPO, VELOCIDADE, DISTANCIA, LITROS_USADOS: real

Inicio
   escreval("Digite o tempo gasto na viagem (em horas): ")
   leia(TEMPO)
   escreval("Digite a velocidade média durante a viagem (em km/h): ")
   leia(VELOCIDADE)

   DISTANCIA <- TEMPO * VELOCIDADE

   LITROS_USADOS <- DISTANCIA / 12

   escreval("Velocidade média: ", VELOCIDADE, " km/h")
   escreval("Tempo gasto na viagem: ", TEMPO, " horas")
   escreval("Distância percorrida: ", DISTANCIA, " km")
   escreval("Quantidade de litros de combustível utilizada: ", LITROS_USADOS, " litros")

Fimalgoritmo
```

# Exercício 7E
```md
algoritmo "exercicio7E-manzano"


var
   valor, taxa, tempo, prestacao: real

inicio
   escreval("Digite o valor da prestação: ")
   leia(valor)
   escreval("Digite a taxa de juros (em %): ")
   leia(taxa)
   escreval("Digite o tempo de atraso (em meses): ")
   leia(tempo)

   prestacao <- valor + (valor * (taxa / 100)) * tempo

   escreval("O valor da prestação em atraso é: R$ ", prestacao)

fimalgoritmo
```

