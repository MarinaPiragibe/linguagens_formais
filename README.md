# linguagens_formais

Casos de Uso

Problema da Parada:
 > entrada: q1bbRq1$
 > saída: loop infinito

Entra em um estado não final que não consegue sair
> entrada: q1a1a11Rq11#q11a1a1Rqf$a1a111
> saída: q1a1a11Rq11#q11a1a1Rqf$a11A111#R

Entrada não tem estado inicial
> entrada: q11a1a11Rq11#q11a1a1Rqf$a1a111
> saída: A MTU rejeita

Entrada não tem estado final nem transição equivalente:
 > entrada: q1bbRq11$
 > saída: q1bbRq11$bA#R

Entrada perfeita!
> entrada: q1a1a11Rq11#q11a11a111Lqf#q11a1a11Rq1$a1a11
> saída: q1a1a11Rq11#q11a11a111Lqf#q11a1a11Rq1$A11a111#A