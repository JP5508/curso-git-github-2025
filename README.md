# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Confira tudo no canal do 'Téo Me Why' no youtube. Segue o link:

[Curso Git 2025](https://www.youtube.com/@teomewhy)

agora eu ja cansei de fazer tudo igual o dele, mas eu to entendendo bem as explicações dele
TMW é brabo

c----

## Fluxo de trabalho Git local**
1. git checkout -b
2. cria ou atualiza arquivos
3. git status
4. git add *arquivos*
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
1. git clone
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add *arquivos*
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add *arquivos*
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>