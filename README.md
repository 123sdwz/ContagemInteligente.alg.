algoritmo "CONTAGEM INTELIGENTE"
var
   I,F,cont :Inteiro

inicio
     escreval("-------------------------")
     escreval("  CONTAGEM INTELIGENTE   ")
     escreval("-------------------------")
     
     Escreva ("INICIO: ")
     leia    (I)
     Escreva ("FIM: ")
     leia    (F)
     escreval("      CONTANDO      ")
     
     Se (F>I) entao
         cont <-I
             enquanto (cont<=F) faca
                  escreva ( cont,"..." )
                       cont<-cont +1
             fimenquanto
     Senao
         cont<-I
             enquanto (cont>=F) faca
                  escreva ( cont,"..." )
                       cont<-cont -1
             fimenquanto
     Fimse

fimalgoritmo
