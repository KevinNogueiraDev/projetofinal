# Conceitos fundamentais de C

## Variáveis e tipos de dados

Variáveis são utilizadas para armazenar valores durante a execução do programa.

int idade = 18;

float altura = 1.81;

char inicial = 'K';

## Os principais tipos básicos são:

int: números inteiros.

float: números decimais.

char: caracteres.

## Entrada e saída

printf() mostra informações na tela e scanf() permite receber dados do usuário.

int idade;

printf("Digite sua idade: ");

scanf("%d", \&idade);

## Operadores

Os operadores permitem realizar cálculos e comparações.

int resultado = 10 + 5;

Alguns operadores são:

+, -, \*, /: operações matemáticas.

%: resto da divisão.

==, !=, >, <: comparação.

## Condições

O if e o else permitem que o programa tome decisões.

if (idade >= 18) {

  printf("Maior de idade");

} else {

  printf("Menor de idade");

}

## Repetições

for e while permitem repetir um conjunto de instruções.

for (int i = 1; i <= 5; i++) {

  printf("%d\\n", i);

}

## Funções

Funções agrupam instruções que realizam determinada tarefa.

int somar(int a, int b) {

  return a + b;

}

## Vetores

Vetores armazenam vários valores do mesmo tipo.

int numeros\[3] = {10, 20, 30};

Em C, o primeiro elemento de um vetor possui índice 0.

## Resumo

Esses conceitos formam a base da programação em C: variáveis, tipos de dados, entrada e saída, operadores, condições, repetições, funções e vetores.
