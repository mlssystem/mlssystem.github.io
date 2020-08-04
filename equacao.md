# [Algoritmo](algoritmo.html)

## Equação

```
algoritmo "equacao"
// Função :
// Autor :
// Data : 05/11/2016
// Seção de Declarações 
var
     a, b, c: Inteiro
     Delta: Real
     x1, x2: Real
inicio
     Escreval ("Equação do Segundo Grau")
     Escreval ("-----------------------")
     Escreva ("Informe o Valor de A:")
     Leia (a)
     Escreva ("Informe o Valor de B:")
     Leia (b)
     Escreva ("Informe o Valor de C:")
     Leia (c)
     Escreval ("-----------------------")
     Escreval ("Sua Equação e: ", a, "x2 +", b, "x +", c, " = 0")
     delta := (b*b) - 4*a*c
     Escreval ("Valor de Delta: ", delta:4:2)
     Se (delta < 0) entao
        Escreval ("Para Delta negativo, não existe raizes Reais")
     senao
           se (delta = 0) entao
              x1 := (-b + raizQ(delta))/(2*a)
              Escreval ("Para Delta zero, temos duas raizes igual a ", x1)
           senao
                x1 := (-b + raizQ(delta))/(2*a)
                x2 := (-b - raizQ(delta))/(2*a)
                Escreval ("Para Delta positivo. Raizes diferentes: ")
                Escreval ("x' = ", x1:4:2)
                Escreval ("x'' = ", x2:4:2)
           fimSe
     FimSe     
fimalgoritmo
```
[<<- voltar](index.html)
