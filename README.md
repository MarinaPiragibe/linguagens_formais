# Linguagens Formais: Máquina de Turing Universal
### Autores: Marina Piragibe e Pedro Ximenes
#### Casos de Uso

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

Loop infinito :O 
> entrada: q1a1a1Rq1#q1bbLq1$a1
> saída: q1a1a1Rq1#q1bbLq1$A1 (infinito)

Entrada que move o cabeçote para a esquerda e encontra $
> entrada: q1a1a1Lq1#q1SSRqf$a1
> saída: q1a1a1Lq1#q1SSRqf$A1#A

Máquina que verifica se o número é primo
>entrada:q1a1a11Rq11#q11a11a11Rq11#q11SSRqf#q11a1a11Rq111#q111bbLqf#q111a1a111Lq1111#q1111a11a1111Rq11111#q1111a1111a1111Lq1111#q1111a111a111Lq1111#q11111a1111a1111Lq11111#q11111a111a111Lq11111#q11111a11a11Rq111111#q11111SSRq1111111#q111111a111a111Rq111111#q111111a1111a1111Rq111111#q111111a1a111Lq1111#q111111bbLq11111111#q1111111a111a111Rq1111111#q1111111a1111a11Rq1111111#q1111111a1a111Lq1111#q11111111a1111a11Lq11111111#q11111111a111a1Lq11111111#q11111111a11a11Rq11$a1a1a1a1a1
>saída:q1a1a11Rq11#q11a11a11Rq11#q11SSRqf#q11a1a11Rq111#q111bbLqf#q111a1a111Lq1111#q1111a11a1111Rq11111#q1111a1111a1111Lq1111#q1111a111a111Lq1111#q11111a1111a1111Lq11111#q11111a111a111Lq11111#q11111a11a11Rq111111#q11111SSRq1111111#q111111a111a111Rq111111#q111111a1111a1111Rq111111#q111111a1a111Lq1111#q111111bbLq11111111#q1111111a111a111Rq1111111#q1111111a1111a11Rq1111111#q1111111a1a111Lq1111#q11111111a1111a11Lq11111111#q11111111a111a1Lq11111111#q11111111a11a11Rq11$a1a1a1a1a1#A
