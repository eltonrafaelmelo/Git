# Git
Comando do git e informações sobre como configurar o gitconfig

GIT INIT:
Para transformar o diretório atual em um repositório do Git, basta executar o comando git init: 
$ git init 

GIT STATUS:
Podemos ver a situação dos arquivos no repositório Git com o comando: 
$ git status

GIT ADD: 
Para que o arquivo seja rastreado, devemos executar o seguinte comando: 
$ git add <arquivo>

GIT PUSH:
para enviar as altureções para o git só executar o comando:
$ git push

GIT CLONE <url repositorio git>:
para baixar um projeto, arquivo ou pasta do git se você é usuario do git basta executar o comando:
$ git clone git@github.com:eltonrafaelmelo/Git.git

GIT LOG:
para ver os comite do repositorio basta executar o comando:
$ git log

LS:
lista os arquivos da pasta:
$ ls

LS -LHA
lista todos os arquivos da pasta até os ocultos:
$ ls -lha

GIT DIFF:
para verificar as alterações antes do commit executer o comando:
$ git diff

GIT RM:
para remover um arquivo do git execute o comando:
$ git rm <arquivo>

GIT MV
para renomear um arquivo execute o comando:
$ git mv oldNome.pdf newNome.pdf

MOVENDO ARQUIVOS PARA OUTRA PASTA
para mover um arquivo para outra pasta já existente basta execultar:
$ git rm arquivo pasta/arquivo

GIT CHECKOUT --<ARQUIVO>
para desfazer uma alteração que ainda não foi commitada execute:
$ git checkout --<arquivo>

GIT RESET --<ARQUIVO>
para terirar o arquivo do git add sem perder suas modificações execute:
$ git reset --<arquivo>


GIT REVERT --NO-EDIT
Se quisermos voltar atrás, desfazendo as alterações no repositório, podemos utilizar o comando:
$ git revert --no-edit <codigo comit>

GIT PUSH
Para enviar os commits locais, que ainda não existem no servidor, devemos utilizar o comando:
$ git push


GIT PULL
para baixar novas atualizações utilizar o comando
$ git pull

GIT BRANCH
Para listar as branches do nosso repositório, devemos executar o comando:
$ git branch

GIT BRANCH <novo branch>
Para criarmos um NOVO branch para trabalharmos basta executarmos:
$ git branch <nome do novo branch>

GIT BRANCH --NO-MERGED
podemos veri car as branches ainda não mescladas com a opção --no-merged do comando git branch:
$ git branch --no-merged

GIT CHECKOUT <Nnome do Branch>
Para trocarmos de branch, devemos executar:
$ git checkout <Nome do branch>

GIT BRANCH -D <Nome do branch>
Para deletar uma branch, devemos utilizar a opção -d do comando git branch:
$ git branch -d <Nome do branch>

GIT RM
para remover um arquivo ou pasta, basta executar:
$ git rm <nome do arquivo>












