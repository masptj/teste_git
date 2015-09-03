#Teste_git

##Exercício do curso "Trabalhando com GIT"

###Meu primeiro `push`

Inicialmente foi iniciado o versionamento do exercício com o comando `git init`.

logo em seguinda todos os arquivos do diretório foram adicionados usando o comando `git add .`.

Por fim foi realizado o commit com o comando `git commit -m "mensagem"`.

##Efetuando o envio dos arquivos para o GitHub

Primeiro é preciso criar um repositório na conta do GitHub, uma vez criado passamos para o envio ao mesmo.

###Para enviar os arquivos ao GitHub, precisamos adicionar o repositório, no meu caso `https://github.com/masptj/teste_git.git`

O comando para adicionar as informações do repositório remoto localmente aqui nomeado "origin": `git remote add origin https://github.com/masptj/teste_git`

O camando para enviar os arquivos locais para o repositório (github): `git push -u origin master`

Com isto teremos os arquivos locais do branch "Master" disponíveis para quem desejar acompanhar e baixar e passar a contribuir.

