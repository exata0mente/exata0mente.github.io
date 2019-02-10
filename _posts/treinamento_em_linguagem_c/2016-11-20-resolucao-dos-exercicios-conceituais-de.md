---
layout: post
title: "Exercício de 1 a 15 e 25 (Conceitos de operadores)"
date: '2016-11-20T04:40:00.001-08:00'
author: Exata0Mente
tags:
- programacao
- linguagem C
- operadores
categories:
- treinamento_em_linguagem_c
- cap2  
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-7724394280978662700
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/resolucao-dos-exercicios-conceituais-de.html
resposta: TRUE
link_resposta: https://github.com/exata0mente/ResolucoesLivros/blob/master/Programacao/Treinamento_em_Liguagem_C/Cap2/Exercicio1_15_25.c
---

Resolução dos exercícios conceituais de 1 a 15 e 25, capítulo 2, do livro da Viviane Victorine Mizrahi, {{ page.book_name }}, 2ª ed.
O capítulo 2 trata especificamente de operadores: aritméticos, relacionais, lógico e atribuição. Neste capítulo
vemos também tabela de precedência dos operadores. As respostas desses exercícios estão em meu github (link no final da página).

**Exercício 1**. Quais dos seguintes operadores são aritméticos?

a) +;  
b) &&;  
c) %;  
d) <;  
e) <<;  

**Exercício 2**. Uma expressão:

a) geralmente avalia um valor numérico;  
b) sempre ocorre fora de qualquer função;  
c) deve ser parte de uma instrução;  
d) indica o estado de emoção do programador;  
e) sempre mistura símbolos com números inteiros;  

**Exercício 3**. Supondo que todas as variáveis são do tipo `int`, encontre o valor de cada uma das expressões a seguir:

a) `x = (2+1)*6;`  
b) `y = (5+1)/2*3;`  
c) `i = j=(2+3)/4;`  
d) `a = 3+2\*(b=7/2);`  
e) `c = 5+10%4/2;`  

**Exercício 4**. Reescreva a seguinte instrução usando operador de incremento.

```c
numero = numero + 1;
```

**Exercício 5**. Como sera interpretada a expressão "`x+++y`"?

a)`x++   +   y`  
b)`x     +   ++y`

Escreva um pequeno programa e verifique a interpretação dada em seu compilador.

**Exercício 6**. Quais são os valores de cada variável nas seguintes expressões?

```c
int a = 1, b = 2, c = 3, d = 4;
```

a) `a += b + c;`  
b) `b *= c = d + 2;`  
c) `d %= a + a + a;`  
d) `d -= c -= b -= a;`  
e) `a += b += c += 7;`  


**Exercício 7**. Os operadores relacionais são usados para:

a) combinar valores;  
b) comparar valores;  
c) distinguir diferentes tipos de variáveis;  
d) trocar variáveis por valores lógicos;  

**Exercício 8**. Quais das seguintes expressões são corretas?

a) `a == 'A'`  
b) `a > b`  
c) `a =< b`  
d) `a > = b`  
e) `-a = b`  
f) `-a = = b`  
h) `a =! b`  
i) `-85.2 >= (x * 45.3 + 32.34)`  
g) `-a == b`  
j) `a + b + c == -x * -y`  
k) `'a' + 'b' != 16 + 'w'`  

**Exercício 9**. Qual e o valor das seguintes expressões?

a) `1 > 2`  
b) `!(1 > 2)`  
c) `3 == 2`  
d) `!(-5)`  
e) `'j' != 'j'`  
f) `'j' != 'j'+ 2`  
g) `'j' != 'j' == 'j'`  

**Exercício 10**. Qual o valor de k?

```c
int k, j = 3;
k = j == 3.
```

**Exercício 11**. Qual o valor de y?

```c
float y;
int x;
x = 22345;
y = (float)(x);
printf("%f", y);
```

**Exercício 12**. Indique o valor de cada uma das seguintes expressões
([consulte a tabela de precedência dos operadores]()).

```c
int i = 1, j = 2, k = 3, n = 2;
float x = 3.3, y = 4.4;
```
a) `i < j + 3`  
b) `2 * i - 7 <= j - 8`  
c) `-x + y >= 2.0 * y`  
d) `x == y`  
e) `x != y`  
f) `i + j + k == -2 * -k`  
g) `!(n-j)`  
h) `!n-j`  
i) `!x * !x`  
j) `i && j && k`  
k) `i || j - 3 && 0`  
l) `i < j && 2 >= k`  
m) `i < j || 2 >= k`  
n) `i == 2 || j == 4 ||  k == 5`  
o) `i = 2 || j == 4 ||  k == 5`  
p) `x <= 5.0 && x != 1.0 || i > j`  

**Exercício 13**. Escreva expressões equivalentes sem usar o operador de negação (!)

a) `!(i == j)`  
b) `!(i + 1 < j - 2)`  
c) `!(i < j && n < m)`  
d) `!(i < 1 || j < 2 && n < 3)`  

**Exercício 14**. Qual o valor das seguintes expressões? 

```c
int a = 1, b = 2, c = 3;

++a/a&&!b&&c||b||-a+4*c>!!b;
```

**Exercício 15**. A expressão seguinte é obscura. Coloque parênteses para torná-la clara: 

```c
a = x < y ? x < z ? x : z : y < z ? y : z;
```

**Exercício 25**. A função `scanf()` retorna o número de leituras feitas com sucesso. Considere o seguinte programa:

```c
#include
#include

int main()
{
  int i, j, k;
  printf("%d\n", scanf("%d %d %d", &i, &j, &k));
  return 0;
}

```
