---
layout: post
title: Exercício 43 - Calendário Gregoriano
date: '2016-11-27T15:02:00.001-08:00'
author: Exata0Mente
tags: [programacao, C, funcoes]
categories:
- treinamento_em_linguagem_c
- cap5
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-5863159863557597126
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/tecl-capitulo-5-exercicio-43-calendario.html
---
**Exercício 43**: Juliana para gregoriana: Escreva uma função que converta uma data juliana em data gregoriana.

A função deverá encontrar o dia, mês e ano correspondente a data juliana que ela recebe como argumento e retornar um numero do tipo `long` no formato aaaammdd. O algoritmo é o seguinte:

B = DataJuliana + 68569  
N = (4 \* B) / 146097  
B = B - ((146097 \* N + 3) / 4)  
K = 4000 \* (B + 1) / 1461001  
B = B - (1461 \* K) / 4 + 31  
J = (80 \* B) / 2447  
Dia = B - (2447 \* J) / 80  
B = (J / 11)  
Mes = J + 2 - (12 \* B)  
Ano = 100 \* (N - 49) + K + B  
