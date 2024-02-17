# Exercício 4

## Faça um algoritimo para ler numero da conta do cliente, saldo,debito e credito. calcular e escrever o saldo atual, testar se o saldo é maior ou igual a 0 escrever a mensagem de positivo e negativo 
algoritmo "Exercicio 4"
```js
// Declaração de variáveis 
var
conta:real // variavel e seu tipo         
debito,credito,saldo,saldoatual:real

inicio // inciando código
// print na tela 
escreva(" digite o numero da sua s conta bancaria     ")
leia(conta) // variavel que armazenas valores digitados
escreva("digite segiu saldo   ") // print na tela
leia(saldo) // variavel que armazena valores digitados
escreva("digite seu valor no debito   ") //print na tela
leia(debito) //variavel que armazena valores 
escreva(" digite seu credito   ") // print na tela
leia(credito) // variavel que armazena valores 
saldoatual <- (saldo + debito) - credito //calculo de variavel
escreva(saldoatual) //print na tela
SE (saldoatual >= 0) ENTAO // SE ENTAO é o if condicional
   escreva("   saldo positivo") // print na tela 
SENAO   // SENAO = o else condicional 
     escreva("  saldo negativo") // print na tela 
FIMSE   // fim da condicional

fimalgoritmo  // fim do codigo 

```
```py
conta = 9084579
saldo = 2400
debito = 900
credito = 400
saldoAtual = 0

saldoAtual = (saldo + credito) - debito
print(saldoAtual)

if saldoAtual >= 0 :
  print(" Saldo positivo")
else:
  print(" Saldo Negativo")

```