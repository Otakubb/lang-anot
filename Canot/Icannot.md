# C anotações (Cannot)
## Estrutura
1. Zona de Includes 
    * Serve para indicar quais as bibliotecas que devem ser "linkadas" ao programa.
    * Correpsondem a headerfiles das bibliotecas do compilador.
    * Ou do próprio programador. 
    * *Sintaxe:*
        ~~~C
        #include <nomedalib.h>
        ~~~
    * Notas:
        * tem de ser um por linha
        * ao contrário da maioria das instruções em C não pode ter ";" no fim.

2. Zona de constantes simbólicas 
    * serve para representar um valor (um número, por exemplo), através de um identificador.
    * um identificador é uma palavra  (nome) contendo letras, digitos ou underscore, com comprimento de 256 cractéres.
        * não pde iniciar com digitos.
        * C é case-sensitive.
    * *Sintaxe:*
        ~~~C
        #define NOME valor
        ~~~
    * Notas 
        * 1 por linha.
        * nome em maiúsculas, não leva ";" no final.
