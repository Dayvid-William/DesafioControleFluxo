# DIO - Trilha Java Básico

## Controle de Fluxo - Desafio

Vamos exercitar todo o conteúdo apresentado no módulo de Controle de Fluxo codificando o seguinte cenário.

O sistema deverá receber dois parâmetros via terminal que representarão dois números inteiros, com estes dois números você deverá obter a quantidade de interações (for) e realizar a impressão no console (System.out.print) dos números incrementados, exemplo:

* Se você passar os números 12 e 30, logo teremos uma interação (for) com 18 ocorrências para imprimir os números, exemplo: `"Imprimindo o número 1"`, `"Imprimindo o número 2"` e assim por diante.
* Se o primeiro parâmetro for MAIOR que o segundo parâmetro, você deverá lançar a exceção customizada chamada de `ParametrosInvalidosException` com a segunda mensagem: "O segundo parâmetro deve ser maior que o primeiro"   


1. Crie o projeto `DesafioControleFluxo`
2. Dentro do projeto, crie a classe `Contador.java` para realizar toda a codificação do nosso programa.
3. Dentro do projeto, crie a classe `ParametrosInvalidosException` que representará a exceção de negócio no sistema. 

## In English

#DIO - Basic Java Trail

## Flow Control - Challenge

Let's practice all the content presented in the Flow Control module by coding the following scenario.

The system must receive two interactions via the terminal that represent two integers, with these two numbers you must obtain the number of interactions (for) and print the incremented numbers in the console (System.out.print), for example:

* If you pass the numbers 12 and 30, we will soon have an interaction (for) with 18 occurrences to print the numbers, for example: `"Printing the number 1"`, `"Printing the number 2"` and so on.
* If the first parameter is GREATER than the second parameter, you must throw a custom exception called `ParametrosInvalidosException` with the second message: "The second parameter must be greater than the first"


1. Create the project `DesafioControleFluxo`
2. Within the project, create the `Contador.java` class to carry out the entire organization of our program.
3. Within the project, create a class `ParametrosInvalidosException` that will represent a business exception in the system.