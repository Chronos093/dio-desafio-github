# Comandos Básicos de Git

<a name="ancora"></a>
 ÍNDICE     | LINK'S 
 -----------|-----------
 GIT CONFIG | [Acessar](#ancora1)
 GIT INIT   | [Acessar](#ancora2)
 GIT ADD    | [Acessar](#ancora3)
 GIT COMMIT | [Acessar](#ancora4)
 GIT PUSH   | [Acessar](#ancora5)
 GIT STATUS | [Acessar](#ancora6)
 GIT CLONE  | [Acessar](#ancora7)
 GIT SHOW   | [Acessar](#ancora8)

<a id="ancora1"></a>

 - **git config**
  >Utilizado para definir valores de configuração. Como no exemplo abaixo.

    `git config --global user.email seu-email@gmail.com`
    `git config --global user.name UserNameGitHub`
<a id="ancora2"></a>

 - **git init**
  >Utilizado para iniciar o git no diretório atual.

    `git init` 
<a id="ancora3"></a>

 - **git add**
  >Utilizado para adicionar arquivos ao índice. 
  
  >Exemplo:

    `git add *`
<a id="ancora4"></a>

 - **git commit**
  >Utilizado para **confirmar as alterações** do diretório local, o git commit não envia o diretório para o GitHub.

    `git commit -m "Descritivo das alterações"`
<a id="ancora5"></a>

 - **git push**
  >Utilizado para o envio do diretório para o o GitHub.

  >Exemplo:

    `git push origin master`
<a id="ancora6"></a>

 - **git status**
  >Utilizado para listar de arquivos alterados juntamente com os arquivos que ainda não foram adicionados ou confirmados.

  >Exemplo:

    `git status`
<a id="ancora7"></a>

 - **git clone**
  >Utilizado para clonar/baixar um diretório do servidor para o local.

  >Exemplo:

    `git clone https://github.com/Chronos093dio-desafio-github.git`
<a id="ancora8"></a>

 - **git show**
  >Para visualizar informações sobre qualquer objeto git, use o comando git show.

  >Exemplo:

    `git show`