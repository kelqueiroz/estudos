# Exercício Condicional 

## Leia 2 notas do aluno calcule a média e se foi aprovado 

```js

algoritmo " Exercicio 11"
// Leia 2 notas do aluno calcule a média e se foi aprovado


var  //Declarando variaveis 

nota1,nota2:inteiro  //variaveis - tipo
media:real


inicio      // inciando código


escreva("digite nota 1  ")  // print na tela 
leia(nota1)           // armazena valor da variavel 

escreva("digite nota 2   ")  // print na tela 
leia(nota2)        // armazena valor da variavel 


media <- (nota1 * nota2) /10 // calculo de media 
escreva(media)  //print na tela 

SE (nota1 >= 7 )ENTAO   // SE ENTAO if condicional
   escreva("Aprovado")  // print na tela 
   
SENAO    // SENAO else condicional 
     escreva("Reprovado") // print na tela 
     
FIMSE  // FIMSE finaliza condicional 

fimalgoritm  // fim do programa 

```
 ##  em python 
```py
# Declaração de variaveis 
nota1 = 6 
nota2 = 9
media= 0
# calculando a média das notas
media = (nota1 * nota2) /10
print(media) # print na tela 

#Condicional if = SE ENTAO 
if (media >= 7): 
  print("Aprovado") #print de exibição na tela
  #Condicional else = SENAO
else:
  print("Reprovado") #Print na tela de exibição

  ```