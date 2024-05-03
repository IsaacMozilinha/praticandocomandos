Olá estou treinando a usar o Git Bash, sim estou indo contra as recomendações do Professor Vitor kkkkkkkk

Coloque seu usuário do git e E-mail da seguinte forma:
git config --global user.email "you@example.com"
git config --global user.name "Your Name"

Crie um repositório no GitHub
Copie a URL

ctrl+V não funciona, apenas Ctrl + Shift + V

Comandos:

git init = Cria um novo repositório no Git

git add <arquivo para enviar>  ou git add . (seleciona todos os arquivos)= Manda os arquivos para staging/stand by

git status = Mostra Status 

git commit -m "Mensagem do commit" = Prepara o arquivo para o repositório, segue o link de boas práticas para mensagens do commit: https://www.dio.me/articles/git-boas-praticas-para-escrita-das-mensagens-de-commits

git branch -M "main" = Renomeia a branch main

git remote add origin <link do repositório>  = linka com o GitHub

git push -u origin main = empurra o arquivo pro github