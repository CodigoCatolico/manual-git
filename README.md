# Manual de Git

Para clonar um repositório basta utilizar o comando:

```
$ git clone git@github.com:CodigoCatolico/manual-git.git
```

Para desenvolver uma alteração no código e sugerir que ela seja feita no repositório vamos utilizar o fluxo de branches e pull requests.

O que é um branch?
- https://git-scm.com/book/pt-br/v2/Branches-no-Git-Branches-em-poucas-palavras#:~:text=Um%20branch%20no%20Git%20%C3%A9,novo%20commit%2C%20ele%20avan%C3%A7a%20automaticamente.
- https://www.google.com/url?sa=i&url=https%3A%2F%2Fdev.to%2Fmalhotramanik%2Fbranching-workflows-for-git-5h1l&psig=AOvVaw2IeXV9rNXvv3o4WXaqXgWa&ust=1634343692593000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCPCy4KaTy_MCFQAAAAAdAAAAABAD

O que é um Pull Request?
- https://gomex.me/2020/07/05/precisamos-falar-sobre-pull-request/#:~:text=O%20pull%20request%2C%20%C3%A9%20o,um%20branch%20do%20pr%C3%B3prio%20reposit%C3%B3rio.
- https://blog.da2k.com.br/2015/02/04/git-e-github-do-clone-ao-pull-request/

Primeiramente estando o branch "main", garanta que você está com a utlima versão do branch "main" e crie um novo branch com os comandos abaixo:

```
$ git checkout main
$ git pull
$ git checkout -b nome-do-novo-branch
```

Faça as alterações que você deseja no seu branch e adicione os commits ao seu branch usando os comandos (por exemplo):

```
$ git add .
$ git commit -m "mensagem de commit"
```

Veja a documentação dos commandos git para ter uma melhor base.
- https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Gravando-Altera%C3%A7%C3%B5es-em-Seu-Reposit%C3%B3rio
- https://git-scm.com/docs/git-add/pt_BR
- https://git-scm.com/docs/git-commit/pt_BR
- https://git-scm.com/docs/git-status/pt_BR

Depois de realizar as suas alterações você pode registrar um pull request para que o código seja integrado ao branch "main".
