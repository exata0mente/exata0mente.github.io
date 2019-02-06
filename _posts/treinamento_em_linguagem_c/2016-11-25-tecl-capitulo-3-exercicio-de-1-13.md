---
layout: post
title:  Exercício de 1 a 13 (Conceitos de Laços)"
date: '2016-11-25T04:16:00.000-08:00'
author: Exata0Mente
tags:
- programação
- linguagem C
- laços
categories:
- treinamento_em_linguagem_c
- cap3  
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-4247464108111957795
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/tecl-capitulo-3-exercicio-de-1-13.html
---
O capítulo 3 aborda um dos pilares da programação estruturada: Laços. Este é um assunto em que todo estudante de
computação tem que dominar, tanto na prática quanto na teoria

**Exercício 1**. Um laço `for` com uma única instrução termina com:

a) virgula;  
b) chave de abertura;  
c) chave de fechamento;  
d) ponto-e-virgula;  

**Exercício 2**. Um laço `while` com uma única instrução termina com:

a) virgula;    
b) chave de abertura;  
c) chave de fechamento;  
d) ponto-e-virgula;  

**Exercício 3**. Um laço `do-while` com uma única instrução termina com:

a) virgula;  
b) chave de abertura;  
c) chave de fechamento;  
d) ponto-e-virgula;  

**Exercícios 4**. Um laço `for` de múltiplas instruções termina com:

a) virgula;  
b) chave de abertura;  
c) chave de fechamento;  
d) ponto-e-virgula;  


*A questão 5 e 6 tem a mesma resposta da questão 4. Sempre que precisar
em um laço várias operações faz-se necessário o uso de chaves.*

**Exercício 7**. As três expressões que compõem a expressão do laço `for` são separadas por \_\_\_\_\_\_\_\_\_\_\_\_\_\_.

**Exercício 8**. Múltiplas expressões de incremento na expressão do laço `for` são separadas por \_\_\_\_\_\_\_\_.

**Exercício 9**. Um laço `do-while` é útil quando seu corpo:

a) nunca é executado;  
b) pode nunca ser executado;  
c) deve ser executado pelo menos uma vez;  
d) termina apos a primeira execução;  

**Exercício 10**. A expressão de inicialização de um laço `for`:

a) nunca é executada;  
b) é executada uma única vez a cada iteracao;  
c) é executada enquanto o laço não termina;  
d) é executada uma vez antes do laço ser iniciado;  

**Exercício 11**. Verdadeiro ou Falso: Os dois fragmentos seguintes produzem o mesmo resultado.

a)
```c
for(i = 0; i < 10; i++)
        for(j = 0; j < 10; j++)
            printf("%d", i + j);
```

b)
```c
for(i = 0, j = 0; i < 10; i++)
        for(; j < 10; j++)
            printf("%d", i + j);
```

**Exercício 12**. Qual é o erro deste programa?

```c
/*Soma dos quadrados*/

#include<stdio.h>

int main(){

    int i;

    for(i = 1; i < 10; i++){

        int soma = 0;
        soma += i*i;

    }

    printf("%d\n", soma);

return 0;
}
```

**Exercício 13**. Qual é a saída do programa seguinte?

```c
#include<stdio.h>

int main(){

    int a;

    for(a = 36; a > 0; a /= 2)
        printf("%d\t", a);
    printf("\n");

return 0;
}
```

**Exercício 14**. Este programa imprime uma letra I bem grande na tela:

```c
/*Imprime a letra I*/

    #include<stdio.h>

    int main(){

        int i = 0;

        printf("IIIIIII\n");

        while(i < 17){

            printf("  III\n");
            i++;
        }
        printf("IIIIIII\n");
        printf("\n");

    return 0;
    }
```

a) modifique o programa para que utilize um laço for no lugar do laço `while`;  
b) construa um programa similar que imprima a letra E;  
c) responda: nesse exemplo, qual dos laços se adapta melhor; Por que?  
