# Algumas anotações sobre Git :notebook:

### Todos os comandos citados abaixo devem ser executados no terminal do Git Bash :exclamation:

- git init - Comando utilizado para iniciar um projeto, criando seu repositório localmente.
- git config - Para configurações do GIT em sua máquina, sendo necessário efetuar ao início de um novo projeto. Muito utilizado para identificação de autores dos commits.
  - git config --global user.email "informe seu email do GitHub"
  - git config --global user.name "informe seu nickname do GitHub"

- git status - Verificar o status das alterações efetuadas
- git add - Adicionar alterações efetuadas a sua nova versão do projeto, preparando para o commit
  - git add .      \
  - git add *      ---- Servem para adicionar todas as alterações efetuadas
  - git add -A    /
  - git add nomeArquivo - Adiciona apenas a alteração efetuada no arquivo específico.

- git commit - Gera uma versão reunindo todas as suas alterações adicionadas anteriormente e subindo para o repositório local.
  - git add commit -m "mensagem" - Efetue sempre o commit desta forma, pois todo commit deve conter uma mensagem /breve descrição relacionado a alterações feitas no projeto.

- git push - Serve para "Empurrar" a versão do repositório atual para o repositório remoto no GitHub.
  - git push origin master - Boa prática de enviar o repositório local para o remoto, definindo o nome como origin e informando que será para a branch master.

- git help - Comando para trazer informações sobre comandos do próprio GitHub
  - git help <comando que se tem dúvida> - Assim você terá informações sobre o comando em questão.



## Links úteis

[Documentação do Git](https://git-scm.com/doc)

[Download do Git](https://git-scm.com/downloads)

[Artigo sobre comandos Git](https://www.codigofonte.com.br/artigos/top-25-comandos-do-git)









