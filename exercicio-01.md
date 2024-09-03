# Código
```JS
Algoritmo "exercicio01-repetição"

var
somaSalario, mediaSalario, salario: real
contador: inteiro

inicio
somaSalario := 0
contador := 1

enquanto contador <=20 faca
      escreval("Digite o salário do funcionário (para números decimais, coloque o '.'): ")
      leia(salario)

      se salario = 0 entao
         contador := 0
      senao
         somaSalario := somaSalario + salario
         contador := contador + 1
      fimse
fimenquanto
   
mediaSalario := somaSalario / (contador - 1)

escreval("Soma dos salários: ", somaSalario)
escreval("Média dos salários: ", mediaSalario)
fimalgoritmo
```

# Fluxograma
![alt text](imagens/exc01.png)