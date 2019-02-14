---
layout: post
title: Exercício de 1 a 28 (Conceitos de Matrizes)
date: '2016-12-19T05:16:00.001-08:00'
author: Exata0Mente
tags: [programacao, C, matrizes, vetores, strings]
categories:
- treinamento_em_linguagem_c
- cap7
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-7041350348859128583
blogger_orig_url: https://exata0mente.blogspot.com/2016/12/tecl-capitulo-7-exercicio-de-1-28.html
---
É muito provável que em códigos mais intermediários você veja uma porção de funções e matrizes. Conforme eu citei nos [exercícios conceituais sobre funções]({{ site.baseurl }}{% post_url treinamento_em_linguagem_c/2016-11-27-tecl-capitulo-5-exercicio-de-1-36 %}) o conhecimento do tópico é de extrema importância para te distanciar do simples calouro de programação. A combinação destes dois conteúdos te deixará sempre um passo a frente.

**Exercício 1**. Uma matriz é uma coleção de variáveis de:

a) diferentes tipos de dados distribuídos pela memória;  
b) tipos de dados similares distribuídos pela memória;  
c) tipos de dados similares em sequência na memória;  
d) diferentes tipos de dados em sequência na memória;  


**Exercício 2**. Em uma declaração de matriz, devem ser especificados t\_\_\_, o n\_\_\_ e o t\_\_\_\_\_\_ da matriz.

**Exercício 3**. A declaração da matriz seguinte é correta?

```c
int mat(25);
```

**Exercício 4**. Qual é o elemento da matriz referenciado por esta expressão?
```c
mat[4]
```

**Exercício 5**. Qual é a diferença entre os números "3" destas duas instruções?
```c
int mat[3];
mat[3] = 5;

```

a) o primeiro especifica um elemento particular e o segundo, um tipo;  
b) o primeiro especifica um tamanho e o o segundo, um elemento particular;  
c) o primeiro especifica um elemento particular e o segundo, o tamanho da matriz;  
d) os dois especificam elementos da matriz;  

**Exercício 6**. O que faz a combinação das instruções seguintes?

```c
#define LIM 50
char coleta[LIM]
```
a) torna `LIM` um índice;  
b) torna `LIM` uma variável;  
d) torna `coleta[]` uma matriz de tamanho `LIM`;  
c) torna `coleta[]` uma matriz do tipo `LIM`;  

**Exercício 7**. Se uma matriz é declarada como:

```c
float preco[MAX]
```
a instrução abaixo é correta para acessar todos os elementos da matriz?

```c
for(int j = 0; j <= MAX; j++)
  scanf("%f", preco[j]);
```

**Exercício 8**. A instrução seguinte é correta para inicializar uma matriz de uma dimensão?
```c
int matriz = {1, 2, 3, 4};
```

**Exercício 9**. O que acontecerá se você colocar tantos valores em uma matriz, na sua inicialização, a ponto de seu tamanho ser ultrapassado? 

a) nada;  
b) possível mau funcionamento do sistema;  
c) uma mensagem de erro do compilador;  
d) outros dados podem ser sobrepostos;  

**Exercício 10**. O que acontecerá se você colocar em uma matriz tão poucos valores na sua inicialização que o seu tamanho não seja atingido? 


a) nada;  
b) possível mau funcionamento do sistema;  
c) uma mensagem de erro do compilador;  
d) os elementos não atingidos serão preenchidos com zeros.  


**Exercício 11**. O que acontecerá se você atribuir um valor a um elemento cujo o índice ultrapasse o tamanho da matriz?

a) o elemento conterá o valor zero;  
b) nada;  
c) outros dados serão sobrepostos;  
d) mau funcionamento do sistema.  

**Exercício 12**. A inicialização abaixo é correta?

```c
int matriz[3][3] = { {1, 2, 3},
                     {4, 5, 6},
                     {7, 8, 9}
                    };

```

**Exercício 13**. Na matriz da questão 12, como poderíamos referenciar o elemento do valor 4?

**Exercício 14**. Se uma matriz foi declarada como: 

```c
int matriz[12];
```

o que representa a palavra matriz?


**Exercício 15**. Se você não inicializar uma matriz, o que seus elementos conterão?

a) zeros;  
b) valores indeterminados;  
c) números em ponto flutuante;  
d) caracteres '\0'.  


**Exercício 16**. Quando uma matriz é passada para uma função como argumento, o que realmente é passado?

a) o endereço da matriz;  
b) os valores dos elementos da matriz;  
c) o endereço do primeiro elemento da matriz;  
d) o número de elementos da matriz.  

**Exercício 17**. Verdadeiro ou Falso: Quando uma função recebe uma matriz do tipo `int` passada como argumento, coloca os valores da matriz em uma posição separada de memória, conhecida somente por essa função.

**Exercício 18**. Em que uma string é semelhante a uma matriz?

a) ambas são matrizes de caracteres;  
b) a matriz é um tipo de string;  
c) acessam funções do mesmo modo;  
d) a string é um tipo de matriz.  

**Exercício 19**. Quais das seguintes afirmações são corretas?

a) `scanf()` encerra a leitura de uma string quando encontra um espaço em branco;  
b) `scanf()` lê um número fixo de caracteres de uma string;  
c) `scanf()` termina a leitura de uma string somente quando é pressionado a tecla [ENTER]  
d) `scanf()` não lê strings.  


**Exercício 20**. Uma string é:


a) uma lista de caracteres;  
b) uma coleção de caracteres;  
c) uma matriz de caracteres;  
d) um conjunto de caracteres;  

**Exercício 21**. "A" é um \_\_\_\_\_\_\_\_\_\_ enquanto 'A' é um \_\_\_\_\_\_\_\_\_\_\_\_\_.

**Exercício 22**. O que é a expressão seguinte?

`"Mesopotamia\n"`

 a) uma variável string;  
 b) uma string matriz;  
 c) uma string constante;  
 d) uma string de caracteres.  

**Exercício 23**. Uma string é terminada pelo caractere \_\_\_\_, que é chamado de \_\_\_\_\_.

**Exercício 24**. A função \_\_\_\_\_\_\_ é projetada especificamente para ler uma string do teclado.

**Exercício 25**. Se você tem declarado uma string como:

```c
char nome[10];
```

e em seu programa você solicita que o usuário forneça o seu nome, o máximo de caracteres que ele deverá digitar é \_\_\_\_;

**Exercício 26**. Qual é a função mais apropriada para ler a string str do teclado?

a) `scanf();`  
b) `gets();`  
c) `printf();`  
d) `puts();`  

**Exercício 27**. Assuma a seguinte inicialização:

```c
char str[] = "Brasileira";
```

como você se refere à string "leira"?

**Exercício 28**. Que expressão você usaria para encontrar um comprimento da string str?
