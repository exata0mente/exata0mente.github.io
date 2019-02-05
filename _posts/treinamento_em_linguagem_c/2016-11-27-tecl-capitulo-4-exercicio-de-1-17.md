--- layout: post title: "\[TeCL\] Capítulo 4 - Exercício de 1 a 17
(Comandos de decisão)" date: '2016-11-27T13:53:00.005-08:00' author:
Exata 0Mente tags: - Treinamento em Linguagem C modified\_time:
'2016-11-27T13:53:46.807-08:00' blogger\_id:
tag:blogger.com,1999:blog-7498010033595457742.post-3833915053243951362
blogger\_orig\_url:
https://exata0mente.blogspot.com/2016/11/tecl-capitulo-4-exercicio-de-1-17.html
---\
Comandos de decisão é outro ponto importantíssimo da programação, aqui
aumenta o leque de possibilidade de interação com o usuário.\
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
estão em meu
[github](https://github.com/exata0mente/Treinamento-em-C/blob/master/Cap4/Exercicio1_17.c).</span></span>
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
**Exercício 1. Numa construção** *if* **sem** *else***, o que acontece
se a condição de teste for falsa?**\
\

    a) o controle procura pelo ultimo else do programa;
        b) nada;
        c) o controle passa para a instrucao seguinte ao if;
        d) o corpo do comando if eh executado

\
**Exercício 2. A principal diferença entre o modo de operação do
comando** *if* **e de um laço** *while* **é:**\
\

    a) A expressao de teste eh avaliada diferentemente;
        b) O corpo de um laco while eh executado sempre, e o do comando if apenas se a condicao de teste for verdadeira;
        c) O corpo de um laco while pode ser executado diversas vezes, enquanto o corpo de um if eh executado uma unica vez;
        d) a expressao de teste eh avaliada antes da execucao do corpo de um while e depois da execucao do corpo de um if;

\
**Exercício 3. O** *else* **de um comando** *if-else* **é executado
quando:**\
\

    a) a expressao de teste do if for falsa;
        b) a expressao de teste do if for verdadeira;
        c) a expressao de teste do else for falsa;
        d) a expressao de teste do else for verdadeira;

\
**Exercício 4. Num programa, o comando** *else* **fara par com qual**
*if***?**\
\

    a) o ultimo if com mesmos requisitos do else;
        b) o ultimo if sem else;
        c) o ultimo if de corpo nao envolto por chaves;
        d) o ultimo if de corpo nao envolto por chaves e sem else;

\
**Exercício 5. A vantagem de uma construção** *switch* **sobre um**
*if-else* **é:**\
\

    a) a condicao default pode ser utilizada no switch;
        b) switch fornece clareza e facilidade de leitura;
        c) os casos de um switch sao avaliados de forma a permitir diversas escolhas;
        d) Varias instrucoes podem ser executadas em cada caso de um switch;

\
**Exercício 6. Verdadeiro ou falso: Toda construção** *switch* **pode
ser transformada em ninhos de** *if-else***.**\
\
**Exercício 7. Verdadeiro ou falso: Todo ninho de** *if-else* **pode ser
transformado numa construção** *switch***.**\
\
**Exercício 8. Um comando** *break***:**\
\

    a) termina o programa;
        b) deve ser utilizado seguindo as instrucoes de cada caso num switch;
        c) causa a saida imediata de um if;
        d) causa a saida imediata de um laco for, while ou do-while;
        e) causa a saida imediata de um switch;

\
**Exercício 9. Um comando** *continue***:**\
\

    a) continua o programa apos uma pausa;
        b) desvia para o proximo caso de um switch;
        c) permite a repeticao continua de um laco;
        d) provoca a proxima iteracao de um laco;

\
**Exercício 10. Verdadeiro ou Falso: A instrução** *goto* **é um método
primitivo de interromper um fluxo de um programa e é desaconselhado em
programação estruturada.**\
\
**<span class="pl-c1">Exercício 11</span>. Converta o fragmento seguinte
para que utilize um laço** *<span class="pl-k">for</span>***.**\
\

    int i = 0;
        loop: printf("%d", (i++));
        goto loop;

\
**Exercício 12. A substituição do código:**\
\

    if(ch >= '0' && ch <= '9')
            continue;
        else
            printf("%c", ch);

        por

        (ch >= '0' && ch <= '9') ? continue : printf("%c", ch);

\
**está errada. Explique.**\
\
**Exercício 13. Substitua o uso do** *if-else* **pelo operador
condicional.**\
\

    if(x > y)
            m = x;
        else
            m = y;

\
**Exercício 14. A sintaxe do laço** *while* **é semelhante a de um**
*if***. Se** i **for uma variável inteira, os dois códigos seguintes
provocarão o mesmo efeito?**\
\

    a) while(i = 8){
                printf("%d    %d    %d   ", i, i + 2, i + 3);
                i = 0;
            }

    b) if(i = 8)
                printf("%d    %d    %d   ", i, i + 2, i + 3);

\
**Exercício 15. O código seguinte é correto?**\
\
\

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

**\
Exercício 16. Modifique o programa "xadrez.c" para imprimir um tabuleiro
maior, que preencha a tela;**\
\
**Exercício 17. Modifique o programa "diagonal.c" para que imprima
quatro linhas: as duas que já estão no programa; a terceira, uma linha
vertical que passa pelo centro do retângulo; e a quarta, uma linha
horizontal que passa pelo mesmo centro. As quatro linhas devem se cruzar
no mesmo ponto.**
