# Exercício 7G
```md
Algoritmo "exercicio7G-manzano"


Var
   A, B, C, D : inteiro
   SOMA_AB, SOMA_AC, SOMA_AD, SOMA_BC, SOMA_BD, SOMA_CD : inteiro
   MULT_AB, MULT_AC, MULT_AD, MULT_BC, MULT_BD, MULT_CD : inteiro

Inicio
   escreval("Digite o valor de A: ")
   leia(A)
   escreval("Digite o valor de B: ")
   leia(B)
   escreval("Digite o valor de C: ")
   leia(C)
   escreval("Digite o valor de D: ")
   leia(D)
   
   SOMA_AB <- A + B
   SOMA_AC <- A + C
   SOMA_AD <- A + D
   SOMA_BC <- B + C
   SOMA_BD <- B + D
   SOMA_CD <- C + D

   MULT_AB <- A * B
   MULT_AC <- A * C
   MULT_AD <- A * D
   MULT_BC <- B * C
   MULT_BD <- B * D
   MULT_CD <- C * D

   escreval("Resultado da soma A + B: ", SOMA_AB)
   escreval("Resultado da soma A + C: ", SOMA_AC)
   escreval("Resultado da soma A + D: ", SOMA_AD)
   escreval("Resultado da soma B + C: ", SOMA_BC)
   escreval("Resultado da soma B + D: ", SOMA_BD)
   escreval("Resultado da soma C + D: ", SOMA_CD)
   
   escreval("Resultado da multiplicação A * B: ", MULT_AB)
   escreval("Resultado da multiplicação A * C: ", MULT_AC)
   escreval("Resultado da multiplicação A * D: ", MULT_AD)
   escreval("Resultado da multiplicação B * C: ", MULT_BC)
   escreval("Resultado da multiplicação B * D: ", MULT_BD)
   escreval("Resultado da multiplicação C * D: ", MULT_CD)

Fimalgoritmo
```

# Exercício 7H
```md
Algoritmo "exercicio7H-manzano"

Var
   C, L, A, V: real

Inicio
   escreval("Digite o valor de Comprimento: ")
   leia(C)
   escreval("Digite o valor de Largura: ")
   leia(L)
   escreval("Digite o valor de Altura: ")
   leia(A)
   
   V := C * L * A

   escreval("Resultado da volume de caixa: ", V)

Fimalgoritmo
```

# Exercício 7I
```md
Algoritmo "exercicio7I-manzano"

Var
   A, B, QUADRADO_DIFERENCA : real

Inicio
   escreval("Digite o valor de A: ")
   leia(A)
   escreval("Digite o valor de B: ")
   leia(B)

   QUADRADO_DIFERENCA := (A - B) ^ 2

   escreval("O quadrado da diferença entre A e B é: ", QUADRADO_DIFERENCA)

Fimalgoritmo
```

# Exercício 7J
```md
Algoritmo "exercicio7J-manzano"

Var
   COTACAO_DOLAR, QUANTIDADE_DOLAR, VALOR_EM_REAL : real

Inicio
   escreval("Digite a cotação do dólar: ")
   leia(COTACAO_DOLAR)
   escreval("Digite a quantidade de dólares que você possui: ")
   leia(QUANTIDADE_DOLAR)

   VALOR_EM_REAL := QUANTIDADE_DOLAR * COTACAO_DOLAR
   
   escreval("O valor em reais é: R$ ", VALOR_EM_REAL)

Fimalgoritmo
```
# Exercício 7K
```md
Algoritmo "exercicio7K-manzano"

Var
   COTACAO_DOLAR, QUANTIDADE_REAL, VALOR_EM_DOLAR : real

Inicio
   escreval("Digite a cotação do dólar: ")
   leia(COTACAO_DOLAR)
   escreval("Digite a quantidade de reais que você possui: ")
   leia(QUANTIDADE_REAL)

   VALOR_EM_DOLAR <- QUANTIDADE_REAL / COTACAO_DOLAR

   escreval("O valor em dólares é: US$ ", VALOR_EM_DOLAR)

Fimalgoritmo
```
# Exercício 7L
```md
Algoritmo "exercicio7L-manzano"

Var
   A, B, C, SOMA_QUADRADOS : real

Inicio
   escreval("Digite o valor de A: ")
   leia(A)
   escreval("Digite o valor de B: ")
   leia(B)
   escreval("Digite o valor de C: ")
   leia(C)

   SOMA_QUADRADOS <- (A ^ 2) + (B ^ 2) + (C ^ 2)

   escreval("A soma dos quadrados de A, B e C é: ", SOMA_QUADRADOS)

Fimalgoritmo
```