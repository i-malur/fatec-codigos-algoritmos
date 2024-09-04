# Código
```md
algoritmo "exercicio6-repetição"
var
   idBoi, pesoBoi, idBoiGordo, idBoiMagro: inteiro
   boiGordo, boiMagro: real

inicio
   boiGordo := 0
   boiMagro := 10000
   para i de 1 ate 90 faca
      escreva("Digite a identificação do boi: ")
      leia(idBoi)
      escreva("Digite o peso do boi: ")
      leia(pesoBoi)

      se pesoBoi > boiGordo entao
         boiGordo := pesoBoi
         idBoiGordo := idBoi
      fimse

      se pesoBoi < boiMagro entao
         boiMagro := pesoBoi
         idBoiMagro := idBoi
      fimse
   fimpara

   escreval("O boi mais gordo é o de identificação ", idBoiGordo, " com peso de ", boiGordo)
   escreval("O boi mais magro é o de identificação ", idBoiMagro, " com peso de ", boiMagro)
fimalgoritmo

```