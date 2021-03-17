Estruturas de Repetição
https://www.youtube.com/watch?v=U5PnCt58Q68&t=206s

Enquanto minha mão for menor = a 5, irá trocar a mão para + 1.
Até chegar em 5 para parar de vez. Lógica de repetição da rotina. Executa 6 vezes, pq a mão começa fechada.


Enquanto não arrumar o quarto você não irá sair do castigo. 

algoritmo "conteAte10"

var
   contador: inteiro
inicio
      contador <- 0
      Enquanto (contador <=10) faca
               EscrevaL (contador)
               contador <- contador + 1
      FimEnquanto
      EscrevaL("Terminei de contar")
fimalgoritmo


Variável contadora, finaliza após perceber o 11.

algoritmo "conteAte10"

var
   contador: inteiro
inicio
      contador <- 10
      Enquanto (contador >=0) faca
               EscrevaL (contador)
               contador <- contador - 1
      FimEnquanto
      EscrevaL("Terminei de contar")
fimalgoritmo


Contar de 0 até onde o usuário quiser. Estruturas Condicionais + Estruturas de Repetição

algoritmo "conteAteX"

var
   valor, contador: inteiro
inicio
      contador <- 1
      Escreva("Quer contar até quanto? ")
      Leia(valor)
      Enquanto (contador <=valor) faca
               EscrevaL (contador)
               contador <- contador + 1
      FimEnquanto
      EscrevaL("Terminei de contar")
fimalgoritmo

algoritmo "conteAte10saltando2"

var
   valor,salto, contador: inteiro
inicio
      contador <- 0
      Escreva("Quer contar até quanto? ")
      Leia(valor)
      Escreva("Qual será o valor do salto? ")
      Leia(salto)
      Enquanto (contador <=valor) faca
               EscrevaL (contador)
               contador <- contador + salto
      FimEnquanto
      EscrevaL("Terminei de contar")
fimalgoritmo


Soma com contagem

 #Contador começa com 1, enquanto o contador for menor ou = a 3 faca, interagir . Vou ter uma variável N que irei digitar esse valor, conforme as vezes que coloquei .
Para somar os valores, irei ter uma variável soma, que começa o programa com valor zero, a cada vez que ler N ,vou fazer que o N entre na soma, irá somar com o zero. Atribuições a variável soma.
Tenho a soma, a minha variável soma estava vazia, li um número , logo será o numero que li mais a soma. Acumulando em S
algoritmo "somadornumerico"

var
   contador,N, S: inteiro
inicio
      contador <- 1
      S <- 0
      Enquanto (contador <=3) faca
               Escreva ("Digite o ", contador, "o. valor: ")
               Leia (N)
                    S <- S+N
               contador <- contador + 1
      FimEnquanto
      EscrevaL("A soma de todos os valores foi ", S)
      EscrevaL("Finalizado")
fimalgoritmo


Cada vez que eu ler N , N for maior que maior valor que esta guardado entao, maior passa a ser o N que acabei de digitar.

algoritmo "somadornumerico"

var
   contador,N, S, maior: inteiro
inicio
      contador <- 1
      S <- 0
      Enquanto (contador <=3) faca
               Escreva ("Digite o ", contador, "o. valor: ")
               Leia (N)
               Se (N > maior) entao
                  maior <- N
	Se (N< menor) entao
	menor <-N
               FimSe
               S <- S+N
               contador <- contador + 1
      FimEnquanto
      EscrevaL("A soma de todos os valores foi ", S)
      EscrevaL("O maior valor digitado foi", maior)

fimalgoritmo

algoritmo "somadorNumerico"
var
   contador, n, s, maior, menor: inteiro
inicio
      contador <- 1

      enquanto (contador <= 3) faca
          escreva("Digite o", contador, "º valor: ")
          leia(n)

          // verifica o maior valor
          se (n > maior) entao
             maior <- N
          fimSe

          // garante que, na primeira iteração (contador = 1), e somente nela,
          // o valor da variável [menor], que inicialmente é 0,
          // seja substituído por um valor qualquer digitado pelo usuário
          se(contador = 1) entao
             menor <- n
          fimSe

          // verifica se o menor valor
          se (n < menor) entao
             menor <- n
          fimSe

          s <- s + n
          contador <- contador + 1
      fimEnquanto

   escreval("A soma de todos os números que você digitou é: ", s)
   escreval("O maior número digitado foi", maior)
   escreval("O menor número digitado foi", menor)

fimAlgoritmo


algoritmo "ConversorDeMoedas"
var
   R, D: Real
inicio
         Escreva("Qual o valor em R$? ")
         Leia(R)
         D <- R/5.80
         Escreva ("O valor convertido de R$ para US$ é:", D:5:2, " dólares" )
fimAlgoritmo

