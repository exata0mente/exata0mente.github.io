--- layout: post title: "\[TeCL\] Capítulo 5 - Exercício 43 - Calendário
Gregoriano" date: '2016-11-27T15:02:00.001-08:00' author: Exata 0Mente
tags: - Treinamento em Linguagem C modified\_time:
'2016-11-27T15:02:21.542-08:00' thumbnail:
https://i.ytimg.com/vi/ga\_eSwyJ\_wc/0.jpg blogger\_id:
tag:blogger.com,1999:blog-7498010033595457742.post-5863159863557597126
blogger\_orig\_url:
https://exata0mente.blogspot.com/2016/11/tecl-capitulo-5-exercicio-43-calendario.html
--- Treinamento em Linguagem C - Viviane Mizrahi\
\
**Exercício 43: Juliana para gregoriana: Escreva uma função que converta
uma data juliana em data gregoriana.**\
**\
A função deverá encontrar o dia, mês e ano correspondente a data juliana
que ela recebe como argumento e retornar um numero do tipo** *long* **no
formato aaaammdd. O algoritmo é o seguinte:**\
\
**  B = DataJuliana + 68569\
  N = (4 \* B) / 146097\
  B = B - ((146097 \* N + 3) / 4)\
  K = 4000 \* (B + 1) / 1461001\
  B = B - (1461 \* K) / 4 + 31\
  J = (80 \* B) / 2447\
  Dia = B - (2447 \* J) / 80\
  B = (J / 11)\
  Mes = J + 2 - (12 \* B)\
  Ano = 100 \* (N - 49) + K + B**\
\
**<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;">[<span style="font-size: x-small;">*Voltar
para o ín<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">di<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">ce</span></span>*</span>](http://exata0mente.blogspot.com/2016/11/indice-do-blog.html)</span></span>**\
\
<div class="separator" style="clear: both; text-align: center;">

</div>

\
\
**<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;"><span style="font-size: x-small;">*<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"> </span></span>*</span></span></span>*Código-fonte
da resposta: [clique aqui](http://adf.ly/1gB9m5)*\

