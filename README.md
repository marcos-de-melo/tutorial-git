# tutorial-git
Um tutorial de comandos para mim do git

# estagios
1º WORKING DIRECTORY

2º STAGING AREA

3º GIT DIRECTORY

# Comandos

git init

git status

git add .

git commit -m "Mensagem de comentário"

git diff -> Mostra o que fou alterado

git diff --staged --> mostra o que foi alterado que esta na stage area

git log --> histório de commit

git log 

git log -p -2 -->

git log --pretty=oneline --> mostra somente a chave e a mensagem do commit

gitk --> mostra ferramenta grafica para mostrar relatórios

git commit --amend -m "mensagem (edição)" --> edita um commit existente

git reset HEAD arquivo.txt --> remove arquivo que está na stage area para ele não ser commitado.

git checkout -- arquivo.txt --> reverte mundanças feitas no arquivo para o ultimo commit

git rm arquivo.txt --> remove o arquivo do diretório


# tags

git tag --> lista as tag já criadas

git tag -a nome-da-tag  "Anotação da tag" --> cria uma tag com o nome e atraves do -a uma anotação também

git tag -a nome-da-tag chave-do-commit-anterior -m "anotação da tag" --> Cria uma tag para commits anteriores

git show nome-da-tag --> mostra mais detalhes da tag indicada

git checkout nome-da-tag --> volta os arquivos para o commit da tag informada

git checkout master -> volta para o branch master

git tag -d nome-da-tag  --> remove a tag

# branchs
git branch --> lista os branchs existentes

git branch nome-do-brach-novo --> Cria um novo branch

git checkout nome-do-branch-novo --> muda para este branch

git checkout -b nome-do-branch-novo --> cria o novo branch e já muda para ele

git checkout master --> troca para o branch master

git merge teste --> adiciona as alteraç~eos

git branch -d teste --> deleta o branch teste

# github

ssh-keygen --> cria uma chave na sua maquina para validar no github

id_rsa.pub -> chave

git clone 

git push origin master





































