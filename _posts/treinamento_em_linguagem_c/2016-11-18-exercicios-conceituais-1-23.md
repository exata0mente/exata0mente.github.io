---
layout: post
title: "Exercício 1 a 23 (Conceitos Básicos)"
date: '2016-11-18T06:45:00.006-08:00'
author: Exata0Mente
tags: [programacao, C, basico]
categories:
- treinamento_em_linguagem_c
- cap1  
book_name: Treinamento em Linguagem C
modified_time: '2016-11-24T11:32:39.353-08:00'
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-8616823830221479438
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/exercicios-conceituais-1-23.html
resposta: TRUE
link_resposta: https://github.com/exata0mente/ResolucoesLivros/blob/master/Programacao/Treinamento_em_Liguagem_C/Cap1/conceitual_ex1_a_23.c
---

Resolução dos exercícios conceituais de 1 a 23, capítulo 1, do livro da Viviane Victorine Mizrahi, {{ page.book_name }}, 2ª ed.

Este capítulo, que tem como título **Conceitos Básicos**, aborda os temas iniciais para inserir-se na programação. Nele é abordado assuntos como tipos de dados, nomes de variáveis, `printf()`, `scanf()` e outros assuntos introdutórios.

O post será aberto a comentários. Como todos sabemos, a lógica, apesar de ter um "único resultado", pode percorrer
por caminhos diferentes.

Esta é uma oportunidade de vermos diferentes tipos de resolução de um mesmo problema. Além da resolução, disponibilizarei um [vídeo]() com os comentários sobre a lógica do problema.

**Exercício 1**: Um dos alunos preparou o seguinte programa e apresentou-o para ser avaliado. Ajude-o.

```c
#include<stdio.h>
#include<stdlib.h>;
int Main{}                                
(
  printf( Existem %d semanas no ano.,52);
  cout << end1;                          
  system("PAUSE");            
  return 0;
)
```

**Exercício 2**: O programa a seguir é correto?

```c
main()                     
{
  printf("Linguagem C");    
  system("pause");         
}
```

**Exercício 3**: Quais os erros do programa a seguir?

```c
main()
{
  int a = 1; b = 2; c = 3;
  printf("Os números são: %d%d%d\n, a, b, c, d);
  system("pause");
}
```

**Exercício 4**: Qual será a impressão obtida por cada uma das seguintes instruções?

```c
#include

int main(){

 printf("\na)\n\tBom dia! Shirley.");
 printf("\nb)Voce ja tomou cafe hoje? \n");
 printf("\nc)\n\nA solucao nao existe!\nNao insista!");
 printf("\nd)Duas\tlinhas\tde\tsaida\nou\tuma?");
 printf("\ne)%s \n%s \n%s \n", "um", "dois", "três");

return 0;
}
```
**Exercício 5**: Qual é a saída do seguinte programa?

```c
#include<stdio.h>
#include<stdlib.h>

int main(){

printf("\n\t\"Primeiro Programa\"");
system("PAUSE");

return 0;
}
```
**Exercício 6**: Qual é a saída do seguinte programa?

```c
#include<stdio.h>
#include<stdlib.h>

int main(){

 printf("%c%c%cPrimeiro Programa", '\n', '\t', '\"')
 printf("%c", '/"');
// system("PAUSE");

return 0;
}
```

**Exercício 7**: Letras maiúsculsa e minúsculas em C são diferentes?

a) Depende da implementação do compilador  
b) Verdadeiro  
c) Falso  

**Exercício 8**: Identifique o tipo das seguintes constantes:

a) `'\\r'`  
b) `2130`  
c) `-123`  
d) `33.28`  
e) `0xFA`  
f) `0101`  
g) `2.0e30`  
h) `'\\xDC'`  
i) `'\\"'`  
j) `'\\\\'`  
k) `'F'`  
l) `0`  
m) `'\\0'`  
n) `"F"`  
o) `-4567.89`  

**Exercício 8**: O que é uma variável?

**Exercício 9**: Um tipo de variável em C define:

a) uma variável armazenada em hexadecimal.  
b) o tamanho de memória em bytes que a variável ocupará.  
c) uma variável em binário.  
d) a base a ser usada no armazenamento da variável.  
e) a forma de armazenamento e de recuperação de um valor.  

**Exercício 10**: Em que partes de um programa em C é possível declarar variáveis?

**Exercício 11**: Quais dos seguintes nomes são válidos para variáveis em C?

a) `3ab`  
b) `\_sim`  
c) `n_a_o`  
d) `98Fim`  
e) `int`  
f) `A123`  
g) `x**x`  
h) `__A`  
i) `__A`  
j) `y-2`  
k) `YYFim`  
l) `\meu`  
m) `*y2`  


**Exercício 12**: Quais das seguintes instruções são corretas?

a) `int a`;  
b) `float b`;  
c) `double float c`;  
d) `unsigned char d`;  
e) `unsigned e`;  
f) `long float f`;  
g) `long g`;  
h) `long double h`;  

**Exercício 13**: O tipo `float` ocupa o mesmo espaço que \_\_\_\_\_\_\_ variáveis do tipo char

**Exercício 14**: Em qual tipo de dado podemos armazenar um número
real?

a) `unsigned int`  
b) `char`  
c) `float`  
d) `long`  

**Exercício 15**. Verdadeiro ou Falso: Tipos de variáveis `long int` podem conceber números não maiores que o dobro do maior valor de uma variável do tipo `short int`.

**Exercício 16**: Qual o trecho do programa que inicializa a variável x?

a) `int x; x = 5;`  
b) `int x = 5;`  
c) `int x, y = 5;`  
d) `x = y`  

**Exercício 17**: Arquivos de inclusão são:

a) bibliotecas  
b) compiladores  
c) arquivos ASCII  
d) linkeditores  

**Exercício 18**: Arquivos de inclusão servem para:

a) auxiliar o compilador a compilar  
b) auxiliar o programador na escrita do programa fonte  
c) executar instruções  
d) incluir programas  

**Exercício 19**. A diretiva `#include` é

a) uma instrução C  
b) uma instrução de linguagem orientada a objetos  
c) uma instrução de pré-processador  
d) um objeto  

**Exercício 20**. Diretivas do pré-processador são executadas pelo:

a) compilador  
b) microprocessador  
c) linkeditor  
d) programa  

**Exercício 21**. Códigos especiais servem para:

a) codificar senha  
b) nomear arquivos escondidos  
c) substituir caracteres que não podem ser digitados no teclado  
d) desenvolver programas codificados  

**Exercício 22**. Qual a diferença no uso de aspas simples e aspas duplas em C?

**Exercício 23.** Quais instruções são corretas:

a)
```c
printf
  ( "Primeiro programa" );
```
b)
```c
printf(
"Primeiro programa"
  );
```

c)
```c
printf("Primeiro
  programa");

```

d)
```c
printf
 (
 "Primeiro programa"
 )
;
```
