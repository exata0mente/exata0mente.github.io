---
layout: post
title: Exercício de 1 a 37 (Conceitos de Funções)
date: '2016-11-27T14:37:00.004-08:00'
author: Exata0Mente
tags:
- programação
- linguagem C
- funções
categories:
- treinamento_em_linguagem_c
- cap5
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-787272965100597556
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/tecl-capitulo-5-exercicio-de-1-36.html
---
Ter conhecimento no uso de funções é o um passo importante para ser um programador. Sabendo funções a organização de seu programa, legibilidade e até nível de processamento pode ser melhorado exponencialmente!

**Exercício 1**. Quais das seguintes razões são válidas para escrever funções:

a) funções usam menos memória do que se repitirmos o mesmo código várias vezes.  
b) rodar mais rápido.  
c) dar um nome a um bloco de código.  
d) funções fornecem um meio de encapsular alguma computação numa caixa preta, que pode ser usada sem preocupação quanto a seus detalhes interno.  
e) dividir uma tarefa em pequenas unidades.  
f) funções mantém variáveis protegidas das outras partes do programa.  
g) ajudar a organizar o programa.  
h) reduzir o tamanho do programa.  
i) para que outros programadores possam usá-las.  

**Exercício 2**. Verdadeiro ou Falso: Uma função pode ser útil mesmo se você não enviar nada a ela e ela não lhe retornar nenhuma informação.

**Exercício 3**. Quais das seguintes instruções constituem uma chamada à função sorte?

a) `sorte = 5`;  
b) `int sorte(){return rand()}`  
c) `x = sorte();`  
d) `int y = sorte() % 10;`  

**Exercício 4**. Qual a diferença entre definir e declarar uma função?

**Exercício 5**. O que são parâmetros de uma função?

a) a parametrização das variáveis recebidas;  
b) as variáveis da função que recebem os valores da função que chama;  
c) os valores retornados da função;  
d) as variáveis visíveis somente pelas funções que chama;  

**Exercício 6**. O protótipo de uma função:

a) pode ser escrito em qualquer lugar do programa;  
b) deve preceder a definição da função e toda chamada a ela;  
c) pode ser suprimido se a função for definida antes de ser chamada;  
d) é uma instrução que pertence ao corpo da função;  


**Exercício 7**. O tipo de uma função:

 a) é definido pelos argumentos que ela recebe;  
 b) é definido pelo valor retornado pelo comando `return`;  
 c) é sempre `void`;  
 d) pode ser qualquer um, exceto `void`;

**Exercício 8**. O comando `return`:

 a) é de uso obrigatório em todas as funções;  
 b) termina a execução da função;  
 c) retorna para o início da função;  
 d) pode retornar um único valor a função que chama;  

**Exercício 9**. Verdadeiro ou Falso: Você pode retornar quantos valores desejar de uma função ao programa chamador usando `return`.

**Exercício 10**. Argumentos de funções podem ser:

 a) constantes;  
 b) variáveis;  
 c) chamadas a funções;  
 d) expressões;  
 e) protótipos de funções;  

**Exercício 11**. Quando argumentos são passados para uma função:

a) a função cria novas variáveis para recebê-lo;  
b) a função acessa as mesmas variáveis da função que chama;  
c) a função pode alterar as variáveis da função que chama;  
d) a função não pode alterar as variáveis da função que chama;  

**Exercício 12**. Uma função que não recebe argumentos é do tipo:

a) `int`;  
b) `void`;  
c) `float`;  
d) Não é possível identificar o tipo da função somente com essa informação.  

**Exercício 13**. Uma função que não retorna nenhum valor é do tipo:

 a) `int`;  
 b) `void`;  
 c) `float`;  
 d) Não é possível identificar o tipo da função somente com essa informação.  

**Exercício 14**. A função a seguir é correta?
```c
float celsius(float fahr);
{
  float c;
  c = (fahr - 32.0) * 5.0 / 9.0;
  return c;
}
```
**Exercício 15**. Verdadeiro ou Falso: Funções podem ser definidas dentro de outras funções, conforme as necessidades do programa.

**Exercício 16**. Verdadeiro ou Falso: As variáveis habitualmente usadas em funções C são acessíveis a todas as outras funções.

**Exercício 17**. Quais das seguintes razões são válidas para o uso de argumentos em funções:

a) indicar à função onde localizar ela mesma na memória;  
b) transmitir informações à função para que ela possa operá-las;  
c) retornar informações provenientes da função ao programa que chama;  
d) especificar o tipo da função;  

**Exercício 18**. Este programa é correto? Por quê?
```c
#include <stdio.h>

void main(){
  float x, y;
  scanf("%f %f", &x, &y);
}

float mul(a, b)
float a, b;
{
  return (a*b)
}

```
**Exercício 19**. Uma função recursiva:

a) é definida dentro de outra função;  
b) contém grandes recursos;  
c) contém uma chamada a ela mesma;  
d) solicita recursos de outros programas;  

**Exercício 20**. As funções recursivas:

a) poupam memória;  
b) poupam tempo de execução;  
c) aumentam a legibilidade do programa;  
d) usam mais memória;  

**Exercício 21**. As classes de armazenamento de uma variável determina:

a) tamanho, endereço e classificação;  
b) tempo de vida, visibilidade e inicialização;  
c) valor armazenado, nível de declaração e forma de armazenamento;  
d) valores default, palavras-chaves e automatização;  


**Exercício 22**. As variáveis das classes \_\_\_\_\_\_\_\_\_\_\_ e \_\_\_\_\_\_\_\_\_\_ são criadas em tempo de compilação.

**Exercício 23**. As variáveis de classes \_\_\_\_\_\_\_\_\_\_\_\_ e \_\_\_\_\_\_\_\_\_\_ são criadas em tempo de execução.

**Exercício 24**. A palavra-chave `extern`:

a) solicita que a variável seja criada em tempo de execução;  
b) cria variáveis externas;  
c) informa ao compilador que a variável foi criada em outra fonte;  
d) determina que a variável em questão manterá o valor zero;

**Exercício 25**. Verdadeiro ou Falso:

a) variáveis externas são visíveis até mesmo a códigos de outros arquivos;  
b) variáveis estáticas externas são visíveis até mesmo a códigos de outros arquivos;  
c) variáveis externas ou estáticas podem ser declaradas em qualquer local do programa;  
d) variáveis estáticas podem ser alteradas por qualquer função.  

**Exercício 26**. As variáveis das classes `static` e `extern` são inicializadas com o valor \_\_\_\_\_\_\_, por falta de inicialização;

**Exercício 27**. As variáveis das classes `auto` e `register` são inicializadas com o valor \_\_\_\_\_\_\_, por falta de inicialização;

**Exercício 28**. Quais das seguintes instruções são incorretas:

a) `auto int x = rand();`  
b) `static int x = rand();`  
c) `extern int x = rand();`  
d) `register int x = rand()`;


**Exercício 29**. A principal tarefa do pré-processador é:

a) auxiliar no desenvolvimento do programa-fonte;  
b) aumentar a velocidade de execução;  
c) converter programas para outra linguagem;  
d) processar o programa em diversas máquinas;  


**Exercício 30**. Explique as semelhanças e diferenças entre o uso da diretiva `#define` e do qualificador `const` para definir constantes.

**Exercício 31**. O que é macro?

a) Uma diretiva `#define` que admite argumentos;  
b) Uma diretiva `#define` que substitui o uso de qualquer função;  
c) Uma diretiva `#define` que a escrita de funções;  
d) Uma diretiva `#define` que retorna um valor.  

**Exercício 32**. A macro a seguir é correta?

```c
#define TROCA(a, b){int t; t = a; b = t;}
```

**Exercício 33**. Escreva uma macro que tenha o valor 1 se o seu argumento for um numero ímpar, e o valor 0 se for par.

**Exercício 34**. Escreva uma macro que encontre o maior entre seus três números.

**Exercício 35**. Escreva uma macro que tenha valor 1 se o seu argumento for um caractere entre 0 e 9, o valor 0 se não for.

**Exercício 36**. Escreva uma macro que converta um dígito ASCII entre 0 e 9 a um valor numérico entre 0 e 9.

**Exercício 37**. O código abaixo é correto para calcular o custo de um pacote postal? Tal custo é igual a uma taxa fixa de vezes a soma da altura, largura e comprimento do pacote:

```c
#define SOMA3(alt, larg, comp) alt + larg + comp
...
custo = taxa * SOMA3(a, 1, c);
```
