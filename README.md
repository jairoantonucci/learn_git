# Projeto para aprender GIT


## Instalar o GIT

    $ sudo apt-get update
    $ apt-get install git
    $ git --version

## Inicializar um repositório GIT

    $ git init
    $ ls -la

## Adicionar as credenciais:

    $ git config --global user.name "<user_name>"
    $ git config --global user.email "<user_email>@github.com"

## Visualizar e editar as cresdencias:

    $ git config --global --edit

## Visualizar e alterar o nome da Branch

    $ git branch
    $ git branch -M main

## Adicionar o arquivo no INDEX

    $ git status
    $ git add <project/README.md>
    $ git status

## Adicionar os arquivo do INDEX para o HEAD

    $ git commit -m "mensagem descritiva do commit" 

## Sincronizar com repositório remoto / github

    $ git remote add origin https://github.com/jairoantonucci/learn_git.git

## Mudanças para o repositório Git remoto

    $ git push -u origin main
    $ git push origin main