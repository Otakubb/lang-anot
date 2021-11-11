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
3. Noção de variáveis
    * correspondem a um espaço em memória 
        * é onde são armazenados os valores manipulados pelo programa
    * são definidas por um identificador (nome) e um tipo de dados
        * o tipo de dados define o alcance da variavel
    * em rigor, em C só existem dois tipos de dados
        * números inteiros
        * números reais
    * embora seja guardado com número inteiro, é comum considerar o tipo de dados caractér
    * Tipos de variavéis 
        * Tipos essenciais
            * Int, número inteiro
            * float, número Real
            * char, caratér
        * Existem vários subtipos baseados nos anteriores, que alteram o sinal e o alcance
            * signed or unsigned
            * short, long (não se usa), long long
            * double (12 casas de precisão)
        * variáveis globais
            * Sintaxe de declaração
                ~~~C
                Tipo valor;
                //exemplos
                int n1,n2,n3 = 3;
                char yo = 'Hello, World!!!';//inicialização com valor diferente
                ~~~
            * as variáveis globais são inicializadas a 0, ou seja, se criarmos uma variavel sem lhe colocarmos o valor ela guarda 0.
            * inicialização com valores diferentes exemplificado no bloco de código escrito acima.
4. Programa principal