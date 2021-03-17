Atribuições

var
	msg: caractere
msg <- “Olá, Mundo!”

Irei atribuir a variável msg, com 


algoritmo "primeiro"
var
     msg: caractere
inicio
   msg <- "Ola,Mundo!"
   Escreva(msg)
fimalgoritmo


algoritmo "primeiro"
var
     msg: caractere
inicio
   msg <- "Ola,Mundo!"
   Escreval("Mensagem ", msg)
fimalgoritmo


algoritmo "MeuNome"
var
   nome: Caractere
inicio
   nome <- "Carlos"
   Escreva("Muito prazer ", nome)
fimalgoritmo


comando Leia


Definimos o Nome da variável

algoritmo "MeuNome"
var
   nome: Caractere
inicio
   Escreva ( "Digite o seu nome: ")
   Leia (nome)
   Escreva("Muito prazer ", nome)
fimalgoritmo



__

algoritmo "Sum_Numbers"
var
   n1, n2: Inteiro
inicio
   Escreva ("Digite um número: ")
   Leia (n1)
   Escreva("Digite outro número: ")
   Leia (n2)
   Escreva("A soma dos números é", n1+n2)
fimalgoritmo


Lembrar de declarar a variável

algoritmo "Sum_Numbers"
var
   n1, n2, S: Inteiro
inicio
   Escreva ("Digite um número: ")
   Leia (n1)
   Escreva("Digite outro número: ")
   Leia (n2)
   S <- n1+n2
   Escreva("A soma dos números é", S)
fimalgoritmo

algoritmo "valores"
var
   n1, n2, S: Inteiro
inicio
   Escreva ("Digite um número: ")
   Leia (n1)
   Escreva("Digite outro número: ")
   Leia (n2)
   S <- n1+n2
   Escreva("A soma de ", n1, " com " ,n2, " é igual a" , S)
fimalgoritmo


Saída mais elegante, e mais fácil de ler. + Interatividade do usuário.

