# Portugol
Algorithm and programming logic study using Portugol - Virtualg
This study have the objective to give me skill to improve my knowledge about programming logic.


Algoritmo "glicose"

Var

   glicose : real

Inicio

      escreval("Digite a medida da glicose: ")
      leia(glicose)

      se glicose <= 100 entao
         escreval("Classificação: normal")
         senao
              se (glicose > 100) e (glicose <= 140) entao
                 escreval("Classificação: elevado")
                 senao
                      escreval("Classificação: diabetes")
         fimse
      fimse

Fimalgoritmo
