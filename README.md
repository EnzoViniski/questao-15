Algoritmo "Pares"

var
   N, quadrado: real
   divi: real

inicio
   // Entrada de dados
   escreva("Digite um número entre 5 e 2000: ")
   leia(N)

   // Validação da entrada
   se (N < 5) ou (N >= 2000) entao
      escreva("Número fora do intervalo permitido!")
   senao
      // Loop para processar números de N até 5
      enquanto (N >= 5) faca
         divi <- N % 2
         se (divi = 0) entao
            quadrado <- N ^ 2
            escreval(N, " ^", N, " = ", quadrado)
         fimse
         N <- N - 1
      fimenquanto
   fimse

fimalgoritmo
