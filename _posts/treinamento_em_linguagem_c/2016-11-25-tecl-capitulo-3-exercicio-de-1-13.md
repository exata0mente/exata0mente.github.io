--- layout: post title: "\[TeCL\] Capítulo 3 - Exercício de 1 a 13
(Conceitos de Laços)" date: '2016-11-25T04:16:00.000-08:00' author:
Exata 0Mente tags: - Treinamento em Linguagem C modified\_time:
'2016-11-25T04:18:39.343-08:00' blogger\_id:
tag:blogger.com,1999:blog-7498010033595457742.post-4247464108111957795
blogger\_orig\_url:
https://exata0mente.blogspot.com/2016/11/tecl-capitulo-3-exercicio-de-1-13.html
---\
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;">O ca<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">pítulo
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">3</span>
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">aborda
um dos pilares da programação estrutu<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">rada<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">:
Laços.</span></span></span></span></span></span>\
\
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">Est<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">e
é um assunto em que todo estudante <span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">de
computação <span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">tem
que dominar, tanto na prática quanto <span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">na
teoria!</span></span></span></span>
</span></span></span></span></span></span>\
\
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">A<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">s
respostas desses exercíci<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">os
estão em meu [github](http://adf.ly/1g5guB).</span></span>
</span></span></span></span></span></span></span></span></span></span></span></span>\
\
<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"> </span></span></span></span></span></span></span></span></span></span></span></span><span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;"><span
style="font-size: small;">[<span style="font-size: x-small;">*Voltar
para o ín<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">di<span
style="font-family: &quot;helvetica neue&quot; , &quot;arial&quot; , &quot;helvetica&quot; , sans-serif;">ce</span></span>*</span>](http://exata0mente.blogspot.com/2016/11/indice-do-blog.html)</span></span>\
\
\
**Exercício 1. Um laço** *for* **com uma única instrução termina com:**\
\

        a) virgula;
        b) chave de abertura;
        c) chave de fechamento;
        d) ponto-e-virgula;

\
\
**Exercício 2. Um laço** *while* **com uma única instrução termina
com:**\
\

        a) virgula;
        b) chave de abertura;
        c) chave de fechamento;
        d) ponto-e-virgula;

\
**Exercício 3. Um laço** *do-while* **com uma única instrução termina
com:**\
\

        a) virgula;
        b) chave de abertura;
        c) chave de fechamento;
        d) ponto-e-virgula;

\
**Exercícios 4. Um laço** *for* **de múltiplas instruções termina
com:**\
\

        a) virgula;
        b) chave de abertura;
        c) chave de fechamento;
        d) ponto-e-virgula;

\
**A questão 5 e 6 tem a mesma resposta da questão 4. Sempre que precisar
em um laço várias operações faz-se necessário o uso de chaves.**\
\
**Exercício 7. As três expressões que compõem a expressão do laço**
*for* **são separadas por \_\_\_\_\_\_\_\_\_\_\_\_\_\_.**\
**\
** **Exercício 8. Múltiplas expressões de incremento na expressão do
laço** *for* **são separadas por \_\_\_\_\_\_\_\_.**\
\
**Exercício 9. Um laço** *do-while* **é útil quando seu corpo:**\
\

        a) nunca é executado;
        b) pode nunca ser executado;
        c) deve ser executado pelo menos uma vez;
        d) termina apos a primeira execução;

\
**Exercício 10. A expressão de inicialização de um laço** *for***:**\
\

    a) nunca eh executada;
        b) eh executada uma unica vez a cada iteracao;
        c) eh executada enquanto o laco nao termina;
        d) eh executada uma vez antes do laco ser iniciado;

\
**Exercício 11. Verdadeiro ou Falso: Os dois fragmentos seguintes
produzem o mesmo resultado.**\
\

    a) for(i = 0; i < 10; i++)
            for(j = 0; j < 10; j++)
                printf("%d", i + j);

    b) for(i = 0, j = 0; i < 10; i++)
            for(; j < 10; j++)
                printf("%d", i + j);

\
**Exercício 12. Qual é o erro deste programa?**\
\

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

\
**Exercício 13. Qual é a saída do programa seguinte?**\
\

    #include<stdio.h>

        int main(){

            int a;

            for(a = 36; a > 0; a /= 2)
                printf("%d\t", a);
            printf("\n");

        return 0;
        }

\
**Exercício 14. Este programa imprime uma letra I bem grande na tela:**\
\

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

        a) modifique o programa para que utilize um laco for no lugar do laco while;
        b) construa um programa similar que imprima a letra E;
        c) responda: nesse exemplo, qual dos lacos se adapta melhor; Por que?

\
\

