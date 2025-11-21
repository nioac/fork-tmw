# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Além disso, vamos trabalhar com GitFlow ao final do curso e Visual Studio Code.

Confira tudo o que temos no nosso YouTube. É gratis!

## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
05. git add *arquivos*
06. git status
07. git commit -m "minha mensagem"
08. git checkout main
09. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
01. Fork do projeto para seu próprio github
02. git clone <endereco do projeto fork>
03. git checkout -b <nova_branch>
04. alterações de arquivos
05. git status
06. git add *arquivos*
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

## Fluxo de trabalho Gitflow (boas práticas)
1. no proprío github criar uma branch "develop"
2. voltar ao depositorio local no terminal bash
3. git fetch (tras todas as branchs que estão no repositorio remoto - github)
4. git checkout develop (entrar na branch develop)
5. git pull origin develop (garante que está atualizado)
6. git checkouth -b doc/readme
7. git commit -m "doc: mudancas no arquivo"

Não se versiona dados somente codigos
criar um arquivo no IDE .gitignore (não verciona os arquivos que estiverem descrito dentro dele como  *.csv , *.xls , *.parquet)
cria-se depois uma pasta para colocar esses arquivos e dentro da pasta cria um outro arquivo .gitkeep
normalmente coloca o link no readme as instruções para baixar os arquivos dos dados


----

