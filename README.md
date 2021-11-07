# dio-takeblip-aplicando-conceitos-git-pratica

  _**Roteiro Live Git Na Prática**_
  
* Inicializar um repositório no git
* Adicionar arquivos aos nossos projetos
* Fazer o envia para a base de controle de versão
* Ignorar arquivos do site
* Trabalhar com branches
* Merge com a master
* Inicializar repositório no GitHub
* Conhecendo a página do GitHub
* Subir nossos arquivos locais
* Clonar os repositorios
* Adicionar em README.md

_**<h2>Codigos Utilizados Live</h2>**_

* git init

* Git add <nome do arquivo>: com este comando adiciono arquivos 
que estão criados no meu workspace para o staging area

* git commit -m 'mensagem de envio'

* .gitignore

* git branch, git checkout, git branch -D list

* git stash / git stash drop stash@{n}

* git stash pop / git stash list

* git merge 
  
  _<h2>Dicas Úteis</h2>_

* Pull sempre que for começar a trabalhar
* Sem commits na master
* Geralmente temos uma branch chamada DEV que receberá todas as features em desenvolvimento.
* Usar uma branch por feature
* Use nomes descritivos para commitar seus arquivos com a nomenclatura fix / feat

* git version

- git log

- git rm -rf node_modules/ --cached
-recursivo e forçada

- git config --global core.editor 'code --wait'

- git branch -m novo nome

- git branch -D nome da branch

- git push origin <nome da branch>

- git merge --abort

- git reset HEAD

- git push -u origin

- git remote add origin https://github.com/mhnakashima/dio-takeblip-aplicando-conceitos-git-pratica.git

- git branch -M main
Isso significa que, ao executar o comando, a branch atual será renomeada para main, mesmo que essa branch já exista (efeito causado pelo --force).

- git push origin branch --delete

- git push -u origin main
