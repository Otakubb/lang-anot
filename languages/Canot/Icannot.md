# C anotações
## Estrutura 
1. Zona de Includes 

    * serve para indicar quais bibliotecas devem ser "linkadas" ao programa 
    * correspondem a headerfiles das bibliotecas do compilador
    * ou bibliotecas criadas pelo próprio programador
    * *Sintaxe:*
        ~~~C
        #include <nomedalib.h>
        //exemplo:
        #include <stdio.h>
        ~~~ 
    * Notas
        * tem de ser um por linha 
        * ao contrário de maioria das instruções em C, esta não leva ";" no final

2. Zona de constantes simbólicas

    * serve para representar um valor ( um número, por exemplo), através de um identificador
    * um identificador é uma palavra (nome) contendo letras, digitos ou underscore, com comprimento de 256 caractéres
        * Não pode iniciar com digitos 
        * C é case-sensitive
    * *Sintaxe:*
        ~~~C
        #define NOME valor
        //exemplo
        #define PI 3.1415926
        ~~~
    * Notas 
        * um por linha
        * Nome em maiusculas, não leva ";" no final
3. Noção de variavéis
    * servem para 