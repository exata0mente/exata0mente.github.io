---
layout: post
title: "Como trabalhar colaborativamente utilizando o GitHub"
date: "2019-03-13 17:05:36 -0300"
---
Este site surgiu como uma possibilidade de trabalhar colaborativamente independente do conteúdo a ser gerado. Dá uma passada na nossa seção de [contribuição](https://exata0mente.com.br/contribua/) e veja como você pode participar.

A ideia desta postagem é trazer um conteúdo que aborde temas importantes para este site: [Git](https://git-scm.com/), [GitHub](https://github.com/) e [trabalho colaborativo](https://opensource.guide/).

Vamos lá!

Primeiramente é importante que você tenha uma conta no GitHub (há outros fornecedores que são igualmente interessantes mas para projetos *open* o GitHub está "1 real" a frente). O processo de abertura de conta é muito simples.

Presumo que chegou a este site já possuindo uma conta, então mãos a obra.

### Ache algum repositório que queira ajudar

No ínicio é difícil saber como e por onde podemos começar, vamos utilizar um repositório simples para que você possa praticar.

Para nossa prática, criamos um repositório que você pode acessar abaixo

https://github.com/exata0mente/hello_world_os

Você pode colocar o que quiser neste repositório. Vamos alterando as definições deles conforme os conteúdos de vocês vão sendo enviados. Vamos ver no que vai dar :smile:.

Caso queira mais projetos para colaborar você pode olhar nossa seção de [projetos](https://exata0mente.com.br/contribua/), até com este site você pode colaborar. [Veja como].

### Fork o repositório

Segundo o [manual do GitHub de fork](https://help.github.com/en/articles/fork-a-repo), um fork nada mais é do que uma cópia de um repositório. Quando damos um fork criamos uma cópia do estado atual deste repositório e associamos ao nosso usuário.

![fork do repositório](/assets/manual/fork_exata0mente.png)

Clique em fork.

Pronto! Um repositório com o mesmo nome estará nos seus repositórios:

https://github.com/SEU_USUARIO/hello_world_os

### Trabalhe localmente

Com o repositório "forkado", vamos fazer as devidas alterações localmente, ou seja, vamos **clonar** o conteúdo deste repositório para nossa máquina e então realizar alterações necessárias.

![clone do repositório](/assets/manual/clonar_exata0mente.png)

Agora vamos usar o git para gerenciar as alterações.

Caso nunca tenha usado o git veja esse [material]().

```bash
git clone git@github.com:exata0mente/hello_world_os.git
```

Pronto, agora todo o conteúdo do repositório que você deu fork está no seu computador.

### Crie um parquinho seguro para todos, uma branch

Como o próprio GitHub [fala](https://help.github.com/en/articles/fork-a-repo#next-steps), criar uma branch permite que você construa novas funcionalidades ou testes coisas sem colocar em risco seu projeto principal.

Para melhor entender, dentro da pasta em que está o seu projeto, rode o seguinte comando:

```bash
$ git branch
> * master
```

Pense que a branch **master** será o seu resultado final. Então para que alguma etapa ainda em desenvolvimento não afete o projeto principal, crie uma branch com um nome que diga o que você está implementando.
> Apenas para contextualizar, imagine que você esteja trabalhando em um projeto com mais de 5 pessoas (chutando baixo) e todos estejam mandando alterações constantemente para a branch **master**. Pense que na master está o resultado final de todo um processo de desenvolvimento finalizado.

Enfim, vamos criar uma branch

```bash
$ git checkout -b insere_meme_no_readme
> Switched to a new branch 'insere_meme_no_readme'
```
Agora sim! Vamos realizar as implementações necessárias, deixar tudo bem documentado, separar em vários **commits** e todas as boas práticas open source que podemos realizar:

```bash
$ vim README.md     # Insiro o meme hehe
$ git add .         # Adiciono a minha alteração para á staged area
$ git commit -m 'Adiciona o meme do Pedrinho no README.md'        # Commito minhas alterações e deixo o arquivo pronto para ser utilizado.
$ git push origin insere_meme_no_readme     # Envio minhas alterações para serem avaliadas
```
Agora estamos quase lá!

### Crie um Pull Request, PR para os mais íntimos

No seu repositório, clique no botão *New Pull Request*

![pull request do repositório](/assets/manual/pr_exata0mente01.png)

Coloque-o então todas as informações pertinentes à implementação que está fazendo. Em seguida, é só enviar o PR e aguardar a confirmação dos mantenedores do repositório.

![pull request do repositório comentario](/assets/manual/pr_exata0mente02.png).

Prontinho! Você deu sua contribuição a um projeto :smile:

Este é um fluxo bem simples de contribuição open source. Abaixo alguns links para que você possa se aprofundar mais.

Até a próxima!

### Referências

[Fork a repo do GitHub](https://help.github.com/en/articles/fork-a-repo)  
[Open Source Guide](https://opensource.guide/)  
[Your first open source contribution: a step-by-step technical guide](https://medium.com/@jenweber/your-first-open-source-contribution-a-step-by-step-technical-guide-d3aca55cc5a6)  
[How to contribute (via pull request) to an open-source GitHub project using your own fork](https://mattstauffer.com/blog/how-to-contribute-to-an-open-source-github-project-using-your-own-fork/)

**Tem algum site com conteúdo que sirva de referência? Coloque o aqui também** :smile:
