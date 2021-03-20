Estrutura inicial ...

algoritmo "somadornumerico"

var
   N, cont, S : inteiro
inicio
      S <- 0
      Cont <- 1
      Enquanto (cont <=3) faca
         Escreva ("Digite o ", cont, "o. valor: ")
         Leia (N)
         S <- S + N
         Cont <- Cont + 1
      FimEnquanto
      EscrevaL("A soma de todos os valores digitados é ", S)
fimalgoritmo


//Criei uma variável resp de resposta como caracter, enquanto a resp for "S" , irá perguntar se quer continuar, coloquei o comando de ler a (resp).
Usuário começou a usar o programa, a resp é sim. por isso declarei ela no início

//Repita é a opção do Enquanto, mas em vez de fazer o teste no início, ele faz no final.
Inverso lógico o que esta em rosa. Ficar de castigo até arrumar o quarto.

algoritmo "Somador"

var
   N, S : Inteiro
   resp: Caractere
inicio
   S <- 0
   Repita
      Escreva ("Digite o valor : ")
      Leia (N)
      S <- S + N
      Escreva ("Você quer continuar? [S/N] ")
      Leia(resp)
   Ate (resp = "N")
   EscrevaL("A soma de todos os valores digitados é ", S)
fimalgoritmo