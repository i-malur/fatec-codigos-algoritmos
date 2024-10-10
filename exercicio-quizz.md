```md
algoritmo "quizz"

var
   erros, acertos, pontuacao: inteiro
   opcao: caractere
   nome: caractere
   vetnome: vetor[1..20] de caractere
   vetpontos: vetor[1..20] de inteiro
inicio

   Escreval("*------------------------------------------------------*")
   Escreval("|                    MENU DE OPÇÕES                    |")
   Escreval("*------------------------------------------------------*")
   Escreval("|  0 - SAIR DO QUIZZ                                   |")
   Escreval("|  1 - INICIAR QUIZZ                                   |")
   Escreval("|  2 - RANKING                                         |")
   Escreval("*------------------------------------------------------*")
   Escreval("O QUE DESEJA FAZER? ")
   leia(opcao)

   se (opcao = "0") entao
      Escreval("Finalizando o quizz.")
   fimse

   se (opcao = "1") entao
      limpatela

      Escreval("Digite o seu nome: ")
      leia (nome)

      acertos <- 0
      erros <- 0
      pontuacao <- 0

      Escreval("--------------------------------------------------------")
      Escreval("|                         QUIZZ                        |")
      Escreval("|                  Primeira Pergunta                   |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("1 - Qual é a capital da França?")
      Escreval("a) Londres ")
      Escreval("b) Berlim")
      Escreval("c) Paris")
      Escreval("d) Roma")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "c") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                   Segunda Pergunta                   |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("2 - Quem escreveu 'Dom Casmurro'?")
      Escreval("a) Machado de Assis ")
      Escreval("b) José de Alencar")
      Escreval("c) Graciliano Ramos")
      Escreval("d) Clarice Lispector")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "a") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                  Terceira Pergunta                   |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("3 - Qual é o elemento químico com símbolo 'O'?")
      Escreval("a) Ouro ")
      Escreval("b) Oxigênio")
      Escreval("c) Ósmio")
      Escreval("d) Cobre")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "b") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                    Quarta Pergunta                   |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("4 - Qual é o maior planeta do sistema solar?")
      Escreval("a) Terra ")
      Escreval("b) Júpiter")
      Escreval("c) Marte")
      Escreval("d) Saturno")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "b") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                   Quinta Pergunta                    |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("5 - Qual é a moeda oficial do Japão?")
      Escreval("a) Dólar ")
      Escreval("b) Euro")
      Escreval("c) Iene")
      Escreval("d) Won")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "c") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                   Sexta Pergunta                     |")
      Escreval("--------------------------------------------------------")
      Escreval(" ")
      Escreval("6 - Qual é o maior oceano do mundo?")
      Escreval("a) Oceano Atlântico ")
      Escreval("b) Oceano Índico")
      Escreval("c) Oceano Pacífico")
      Escreval("d) Oceano Ártico")
      Escreval("Resposta:")
      leia(opcao)
      se(opcao = "c") entao
         acertos <- acertos + 1
         pontuacao <- pontuacao + 100
      senao
         erros <- erros + 1
      fimse

      limpatela
      Escreval("--------------------------------------------------------")
      Escreval("|                        QUIZZ                         |")
      Escreval("|                 Obrigada por participar!!            |")
      Escreval("--------------------------------------------------------")

      Escreval(" ")
      Escreval("***********************************************************")
      Escreval("                  Parabéns: ", nome,"                      ")
      Escreval("                  Você acertou: ", acertos,"               ")
      Escreval("                  Você errou: ", erros,"                   ")
      Escreval("                  Você fez: ", pontuacao," pontos          ")
      Escreval("***********************************************************")
   fimse

   se (opcao = "2") entao
      vetnome[1..20] <- nome
      vetpontos[1..20] <- pontuacao
      Escreval(nome, ", sua pontuação é: ", pontuacao)
   fimse
fimalgoritmo




```
