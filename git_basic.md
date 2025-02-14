# COMANDOS BÁSICOS DO GIT
`git config --global user.name "Seu Nome"` -> Inclui a credencial do seu nome
`git config --global user.email "seu_email@example.com"` -> Inclui a credencial do seu email

`git init` -> Inicializa o repositório local

`git status` -> mostra se os arquivos estão dentro do repositório local ou não

`git add "nome_do_arquivo"` -> Você adiciona somente o arquivo que tá no comando

`git add .` -> Adiciona todos os arquivos que estão em vermelhos

Trocando "master" pra "main"
`git branch -M main`-> Troca o nome do branch principal de master pra main

`git commit -m "Mensagem de Atualização` -> Cria um commit para que seja realizado um novo versionamento

No repositório local:
`git log` -> Lista todos os commits que foram realizados.

Atalho pra mostrar o commit em uma unica linha (útil para um repositório cheio de commits)
`git log --oneline --graph --decorate`

`git remote add origin https://github.com/andre-fe-santana/nome_do_seu_repositorio` -> sincroniza o repositorio local com o repositorio do servidor

`git push -u origin main` -> manda os arquivos do repositório local pro repositorio remoto
-u