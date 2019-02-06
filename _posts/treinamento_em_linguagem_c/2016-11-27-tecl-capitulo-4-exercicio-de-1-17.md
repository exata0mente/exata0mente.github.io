---
layout: post
title: "Exercício de 1 a 17 - Comandos de decisão"
date: '2016-11-27T13:53:00.005-08:00'
author: Exata0Mente
tags:
- programação
- linguagem C
- comandos de decisão
categories:
- treinamento_em_linguagem_c
- cap4
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-3833915053243951362
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/tecl-capitulo-4-exercicio-de-1-17.html
---

Comandos de decisão é outro ponto importantíssimo da programação, aqui aumenta o leque de possibilidade de interação com o usuário.

**Exercício 1**. Numa construção `if` **sem** `else`, o que acontece se a condição de teste for falsa?

a) o controle procura pelo ultimo `else` do programa;  
b) nada;  
c) o controle passa para a instrução seguinte ao `if`;   
d) o corpo do comando `if` é executado;  

**Exercício 2**. A principal diferença entre o modo de operação do comando** `if` **e de um laço** `while` é:

a) A expressão de teste é avaliada diferentemente;  
b) O corpo de um laço `while` é executado sempre, e o do comando `if` apenas se a condição de teste for verdadeira;  
c) O corpo de um laço `while` pode ser executado diversas vezes, enquanto o corpo de um `if` é executado uma única vez;  
d) a expressão de teste é avaliada antes da execução do corpo de um `while` e depois da execução do corpo de um `if`;  


**Exercício 3**. O `else` de um comando *if-else* é executado quando:

a) a expressão de teste do `if` for falsa;  
b) a expressão de teste do `if` for verdadeira;  
c) a expressão de teste do `else` for falsa;  
d) a expressão de teste do `else` for verdadeira;  

**Exercício 4**. Num programa, o comando `else` fará par com qual `if`?


a) o ultimo `if` com mesmos requisitos do `else`;  
b) o ultimo `if` sem `else`;  
c) o ultimo `if` de corpo não envolto por chaves;  
d) o ultimo `if` de corpo não envolto por chaves e sem `else`;  

**Exercício 5**. A vantagem de uma construção `switch` sobre um *if-else* é:

a) a condição *default* pode ser utilizada no `switch`;  
b) `switch` fornece clareza e facilidade de leitura;
c) os casos de um `switch` são avaliados de forma a permitir diversas escolhas;  
d) Varias instruções podem ser executadas em cada caso de um `switch`;  

**Exercício 6**. Verdadeiro ou falso: Toda construção `switch` pode ser transformada em ninhos de *if-else*.

**Exercício 7**. Verdadeiro ou falso: Todo ninho de *if-else* transformado numa construção `switch`.

**Exercício 8**. Um comando `break`:

a) termina o programa;  
b) deve ser utilizado seguindo as instruções de cada caso num `switch`;  
c) causa a `saída` imediata de um `if`;  
d) causa a saída imediata de um laço `for`, `while` ou `do-while`;  
e) causa a saída imediata de um `switch`;  

**Exercício 9**. Um comando `continue`:

a) continua o programa após uma pausa;  
b) desvia para o próximo caso de um `switch`;  
c) permite a repetição continua de um laço;  
d) provoca a próxima iteração de um laço;  

**Exercício 10**. Verdadeiro ou Falso: A instrução `goto` é um método primitivo de interromper um fluxo de um programa e é desaconselhado em programação estruturada.

**Exercício 11**. Converta o fragmento seguinte para que utilize um laço `for`.

```c
int i = 0;
loop: printf("%d", (i++));
goto loop;
```

**Exercício 12**. A substituição do código:

```c
if(ch >= '0' && ch <= '9')
  continue;
else
  printf("%c", ch);
```
por

```c
(ch >= '0' && ch <= '9') ? continue : printf("%c", ch);
```

**está errada**. Explique.

**Exercício 13**. Substitua o uso do *if-else* pelo operador condicional.

```c
if(x > y)
    m = x;
else
    m = y;
```

**Exercício 14**. A sintaxe do laço `while` é semelhante a de um `if`. Se **i** for uma variável inteira, os dois códigos seguintes provocarão o mesmo efeito?

a)
```c
while(i = 8){
  printf("%d    %d    %d   ", i, i + 2, i + 3);
  i = 0;
}
```

b)
```c
if(i = 8)
  printf("%d    %d    %d   ", i, i + 2, i + 3);

```
**Exercício 15**. O código seguinte é correto?

```c
switch (temp){
case temp < 10:
    printf("Esta verdadeiramente frio!");
    break;
case temp < 25:
    printf("Que tempo agradavel!");
    break;
default:
    printf("Certamente esta quente!");
    break;
}
```


**Exercício 16**. Modifique o programa "xadrez.c" para imprimir um tabuleiro maior, que preencha a tela;

**Exercício 17**. Modifique o programa "diagonal.c" para que imprima quatro linhas: as duas que já estão no programa; a terceira, uma linha vertical que passa pelo centro do retângulo; e a quarta, uma linha horizontal que passa pelo mesmo centro. As quatro linhas devem se cruzar no mesmo ponto.
