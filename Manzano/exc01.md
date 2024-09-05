```md
var
   a, b, x, y, h, alfa, c, w, delta, resultado1, resultado2: real

inicio
   // Entrada de valores pelo usuário
   escreval("Digite o valor de a: ")
   leia(a)
   
   escreval("Digite o valor de b: ")
   leia(b)
   
   escreval("Digite o valor de alfa: ")
   leia(alfa)
   
   escreval("Digite o valor de x: ")
   leia(x)
   
   escreval("Digite o valor de y: ")
   leia(y)
   
   escreval("Digite o valor de h: ")
   leia(h)
   
   escreval("Digite o valor de c: ")
   leia(c)
   
   escreval("Digite o valor de w: ")
   leia(w)

   // Expressão A
   escreval("A. Resultado: ", a + b * (1 / 3))

   // Expressão B
   escreval("B. Resultado: ", 43 * (55 / (30 + 2 * alfa)))

   // Expressão C
   escreval("C. Resultado: ", ((2 * x^2 - 3 * x^(x + 1)) / 2) + (raizq(x + 1) / x))

   // Expressão D
   escreval("D. Resultado: ", 2 * h - ((45 / (3 * h) - 4 * h * (3 - h))^2))

   // Expressão E
   escreval("E. Resultado: ", (raizq(6^x + 2 * y) / 3^w))

   // Expressão F (Cálculo dos dois possíveis resultados)
   delta <- b^2 - 4 * a * c
   
   se delta < 0 entao
      escreval("F. Não foi possível calcular, pois o delta é negativo.")
   senao
      resultado1 <- (-b + raizq(delta)) / (2 * a)
      resultado2 <- (-b - raizq(delta)) / (2 * a)

      escreval("F. Resultado 1: ", resultado1)
      escreval("F. Resultado 2: ", resultado2)
   fimse

fimalgoritmo
```