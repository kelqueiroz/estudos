# Estudo Git

Criando um repositório no GitHub.

## 1- Passo a Criando um repositório no Github

* Acesso ao Github
* Clicar no sinal de +
* Clicar em New Repository
* Abrirá a página de criação de repositório
* Coloque o nome do repositório
* Opção público ou privado
* Colocar se irá gerar "REDME"
* Colocar se irá gerar "gitignore"
* Clicar em "Creat Repository".
## 2. Configurar Repositório Local

Agora o site do Github deve mostrar a página de configuração para o repositório local ser sincronizado. Abra o seu projeto na sua IDE ou via o terminal navegue até a pasta do seu projeto e use os comandos abaixo.

* Executando o repositório local
    > git init
* Adicionando os arquivos para Commit "ENIVAR"
    > git add .
    
    _Obs: o comando add sem o ponto enviará um arquivo específico, o comando add seguido de ponto enviará todos os arquivos do projeto._

* Criando um comentário para o commit(enviar) dos arquivos

> git commit -m "publicando projeto"

* Atribuir a branch "main" do  repositório   
    > git branch -M main

* Configurando o endereço nuvem do repositório.

> git remote add origin https://github.com/kelqueiroz/git-teste.git

* Enviando os arquivos do repositório local para a nuvem. 

> git push -u origin main







