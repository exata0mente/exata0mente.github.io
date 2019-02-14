---
layout: post
title: Exercício 41 - Calendário Juliana
date: '2016-11-27T14:54:00.003-08:00'
author: Exata0Mente
tags: [programacao, C, funcoes]
categories:
- treinamento_em_linguagem_c
- cap5
book_name: Treinamento em Linguagem C
blogger_id: tag:blogger.com,1999:blog-7498010033595457742.post-6901701425954346839
blogger_orig_url: https://exata0mente.blogspot.com/2016/11/tecl-capitulo-5-exercicio-41-numeros.html
---

**Exercício 41**: Gregoriana para juliana: dados dia, mês e ano de uma data gregoriana, escreva uma função que converta essa data para a data juliana correspondente. Utilize a seguinte fórmula:

Data Juliana =  (1461 \* (ano + 4800 + (mes - 14) / 12)) / 4 + (367 \* (mes - 2 - 12 \* ((mes - 14) / 12))) / 12 - (3 \* ((ano + 4900 + (mes - 14) / 12) / 100)) / 4 + dia - 32075
