# dio-desafio-github-primeiro-repo
## DIO - Desafio criando primeiro projeto GitHub  
-------------------------------------------------

Como projeto prático para entrega do desafio resolvi fazer um apanhado de informações a respeito do GitHub e compartilhar conceitos básicos.
Visão geral
O Git é um sistema de controle de versão de código-fonte aberto, onde várias pessoas podem trabalhar de forma colaborativa em um mesmo projeto por meio do controle de versão distribuída de arquivos que residem em repositórios. 
O GitHub é um serviço de hospedagem na Web para repositório git, por exemplo seu próprio projeto que você cria na sua máquina. 
O Git usa uma estrutura de camadas para gerenciar conteúdo de um projeto:
- Repositório ou repo: É a maior unidade de armazenamento e contém uma ou mais branch.
- Branch: É a unidade de armazenamento que contém os arquivos e as pastas que compões o conjunto de conteúdo de um projeto. As branches separam fluxos de trabalho (conhecidos como versões).
A forma de colaboração para manipular e atualizar o Git se dá no nível local e do GitHub:
- Local, através de ferramentas de suporte como console Git Bash, por meio de comandos é possível gerenciar repositórios local e comunicação com repositórios do GitHub.
Abaixo segue uma lista básica de comandos do Git, lembrando que para utilização e manipulação do GitHub, você deve criar uma conta antes no endereço [Acesso a página do GitHub](www.github.com) e para rodar os comandos local você deve instalar o GitBash na sua máquina fazendo download [Download GitBash](https://git-scm.com/downloads)
Criando projeto no GitHub:
- Acessar sua conta do GitHub e seguir os passos abaixo 
 - Create a new repositor
     . Repository name: ex “dio-desafio-github-primeiro-repo”
     
     . Description(optional) “DIO - Desafio criando primeiro projeto GitGub 
     
     . Public(marcar) “Caso tenha interesse que outras pessoas contribua com projeto”
     
     . Add a README file (você pode marcar para adicionar informações ao seu projeto) 
     
     .Create Repository (Após clicar seu projeto será criado)

Agora com projeto criado na nuvem é possível interagir por meio de comandos localmente e na web
Com o GitBash aberto na pasta local do seu projeto do seu projeto

. Clonar um repositório local ou remoto

  $ git clone
  
. Verificar estado dos arquivos/diretórios 

  $ git status

. Adicionar um arquivo especifico 

  $ git add meu_arquivo.txt

. Adicionar um diretório especifico 

  $ git add meu_diretorio

. Adicionar todos arquivos/diretórios

  $ git add .

Comitar arquivo/diretório

. Comitar arquivo 

 $ git commit meu_arquivo.txt

. Comitar vários arquivos  

 $ git commit meu_arquivo.txt meu_outro_arquivo.txt

. Comitar informando mensagem

 $ git commit meuarquivo.txt -m "minha mensagem de commit"

Remover arquivo/diretório

. Remover arquivo

 $ git rm meu_arquivo.txt

. Remover diretorio

 $ git rm -r diretório
 
 Por: Daniel Machado 
 obs: Explorando conceitos "Criando seu Primeiro Repositório no GitHub" no curso de Venilton, Tech Lead na DIO.
