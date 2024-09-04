# Código
```md
algoritmo "exercicio8-repeticao"


var
   time, cidade, i: inteiro
   salario, somaSalarioBotafogo: real
   torcedoresFlu, torcedoresBotafogo, torcedoresVasco, torcedoresFlamengo, torcedoresOutros: inteiro
   qtdMoradoresRJOutrosTimes, qtdMoradoresNiteroiFlu, qtdTorcedoresBotafogo: inteiro
   qtdEntrevistados: inteiro

inicio
   torcedoresFlu := 0
   torcedoresBotafogo := 0
   torcedoresVasco := 0
   torcedoresFlamengo := 0
   torcedoresOutros := 0
   somaSalarioBotafogo := 0
   qtdMoradoresRJOutrosTimes := 0
   qtdMoradoresNiteroiFlu := 0
   qtdTorcedoresBotafogo := 0

   escreva("Quantas pessoas serão entrevistadas? ")
   leia(qtdEntrevistados)

   para i de 1 ate qtdEntrevistados faca
      escreval("Entrevistado ", i)
      escreval("Qual o seu time de coração? (1-Fluminense; 2-Botafogo; 3-Vasco; 4-Flamengo; 5-Outros)")
      leia(time)
      escreval("Onde você mora? (1-RJ; 2-Niterói; 3-Outros)")
      leia(cidade)
      escreval("Qual o seu salário?")
      leia(salario)
      escolha time
         caso 1
            torcedoresFlu := torcedoresFlu + 1
            se cidade = 2 entao
               qtdMoradoresNiteroiFlu := qtdMoradoresNiteroiFlu + 1
            fimse
         caso 2
            torcedoresBotafogo := torcedoresBotafogo + 1
            somaSalarioBotafogo := somaSalarioBotafogo + salario
            qtdTorcedoresBotafogo := qtdTorcedoresBotafogo + 1
         caso 3
            torcedoresVasco := torcedoresVasco + 1
         caso 4
            torcedoresFlamengo := torcedoresFlamengo + 1
         caso 5
            torcedoresOutros := torcedoresOutros + 1
            se cidade = 1 entao
               qtdMoradoresRJOutrosTimes := qtdMoradoresRJOutrosTimes + 1
            fimse
      fimescolha
   fimpara
   escreval("Número de torcedores por clube:")
   escreval("Fluminense: ", torcedoresFlu)
   escreval("Botafogo: ", torcedoresBotafogo)
   escreval("Vasco: ", torcedoresVasco)
   escreval("Flamengo: ", torcedoresFlamengo)
   escreval("Outros: ", torcedoresOutros)

   se qtdTorcedoresBotafogo > 0 entao
      escreval("Média salarial dos torcedores do Botafogo: ", somaSalarioBotafogo / qtdTorcedoresBotafogo)
   senao
      escreval("Não há torcedores do Botafogo.")
   fimse

   escreval("Número de pessoas moradoras do RJ, torcedoras de outros clubes: ", qtdMoradoresRJOutrosTimes)
   escreval("Número de pessoas de Niterói torcedoras do Fluminense: ", qtdMoradoresNiteroiFlu)

fimalgoritmo
```
