# Aprendendo Git
Esse arquivo irá ter todos os comandos do curso de Git.

```shell
$ git config --global user.name "Nome"
$ git config --global user.email "email@email.com"
$ git init
$ git status
```

## Comandos de log

```shell
$ git log
$ git log --full-diff -p <file>
```

## Checkout

```shell
$ git checkout -- <file> #Desfazer a mudança no arquivo <file>
```

## Trabalhando com branchs

```shell
$ git checkout -b <name> #cria e faz checkout na nova branch
$ git checkout <name> #Alterna entre as branchs
```

## Trabalhando com tags

```shell
$ git tag #lista as tags
$ git tag -a <tag> -m <message> #adiciona uma nova tag
$ git tag -d <tag>  #apaga a tag
```
