# Exercício Calculadora plano de saúde
* Efetue o calculo do valor  do plano de saúde em relação  a idade e sexo do paciente.  Se a operadora calcular o valor do plano igualmente independente do sexo, ou seja, não distingue o valor entre homens e mulheres, então calcule de acordo com a tabela da operadora. Escolha como exemplo uma operadora real.
* Plano usado: [Amil One](https://planodesaudeamil.com/planos-de-saude/tabela-de-precos/)  
![image](https://github.com/user-attachments/assets/a574c75e-eab4-4540-8208-d3289cee7384)

# Código 
```md
algoritmo "CalculoPlanoDeSaudeComLoop"
var
    idade: inteiro
    plano, resposta, nome: caractere
    valor: real

inicio
    escreval("Demonstrativo do plano Amil One")
    escreval("Para conferir a tabela de preços, acesse: https://planodesaudeamil.com/planos-de-saude/tabela-de-precos/")
    repita
    
        escreval("Digite seu nome: ")
        leia(nome)
        escreva("Digite sua idade: ")
        leia(idade)
        escreva("Digite o plano escolhido (S1500, S2500, S6500): ")
        leia(plano)

        se (idade >= 0) e (idade <= 18) entao
            se plano = "S1500" entao
                valor <- 831.83
            senao
                se plano = "S2500" entao
                    valor <- 941.91
                senao
                    valor <- 1210.51 // S6500
                fimse
            fimse
        senao
            se (idade >= 19) e (idade <= 23) entao
                se plano = "S1500" entao
                    valor <- 973.24
                senao
                    se plano = "S2500" entao
                        valor <- 1102.03
                    senao
                        valor <- 1416.30 // S6500
                    fimse
                fimse
            senao
                se (idade >= 24) e (idade <= 28) entao
                    se plano = "S1500" entao
                        valor <- 1187.37
                    senao
                        se plano = "S2500" entao
                            valor <- 1344.48
                        senao
                            valor <- 1727.89 // S6500
                        fimse
                    fimse
                senao
                    se (idade >= 29) e (idade <= 33) entao
                        se plano = "S1500" entao
                            valor <- 1424.83
                        senao
                            se plano = "S2500" entao
                                valor <- 1613.38
                            senao
                                valor <- 2073.47 // S6500
                            fimse
                        fimse
                    senao
                        se (idade >= 34) e (idade <= 38) entao
                            se plano = "S1500" entao
                                valor <- 1645.68
                            senao
                                se plano = "S2500" entao
                                    valor <- 1694.05
                                senao
                                    valor <- 2177.14 // S6500
                                fimse
                            fimse
                        senao
                            se (idade >= 39) e (idade <= 43) entao
                                se plano = "S1500" entao
                                    valor <- 1538.02
                                senao
                                    se plano = "S2500" entao
                                        valor <- 1863.46
                                    senao
                                        valor <- 2394.85 // S6500
                                    fimse
                                fimse
                            senao
                                se (idade >= 44) e (idade <= 48) entao
                                    se plano = "S1500" entao
                                        valor <- 2057.11
                                    senao
                                        se plano = "S2500" entao
                                            valor <- 2329.33
                                        senao
                                            valor <- 2993.56 // S6500
                                        fimse
                                    fimse
                                senao
                                    se (idade >= 49) e (idade <= 53) entao
                                        se plano = "S1500" entao
                                            valor <- 2262.82
                                        senao
                                            se plano = "S2500" entao
                                                valor <- 2562.26
                                            senao
                                                valor <- 3292.92 // S6500
                                            fimse
                                        fimse
                                    senao
                                        se (idade >= 54) e (idade <= 58) entao
                                            se plano = "S1500" entao
                                                valor <- 2828.53
                                            senao
                                                se plano = "S2500" entao
                                                    valor <- 3202.83
                                                senao
                                                    valor <- 4116.15 // S6500
                                                fimse
                                            fimse
                                        senao
                                            se idade >= 59 entao
                                                se plano = "S1500" entao
                                                    valor <- 4949.89
                                                senao
                                                    se plano = "S2500" entao
                                                        valor <- 5604.95
                                                    senao
                                                        valor <- 7203.26 // S6500
                                                    fimse
                                                fimse
                                            fimse
                                        fimse
                                    fimse
                                fimse
                            fimse
                        fimse
                    fimse
                fimse
            fimse
        fimse

        escreval("O valor do plano de saúde é: R$ ", valor:7:2)

        escreva("Deseja calcular outro plano de saúde? (sim/nao): ")
        leia(resposta)
        
    ate resposta <> "sim"
fimalgoritmo





```
