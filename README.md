
 
# Docker to do list

# Contexto

Projeto desenvolvido para aplicar e praticar os conhecimentos adquiridos de Docker

## Técnologias usadas

Docker

## Requisitos 

     - Criar um novo container de modo interativo sem roda-lo nomeando-o como `01container` e utilizando a imagem `alpine` usando a versão `3.12`
     - Iniciar o container `01container`
     - Listar os containers filtrando pelo nome `01container`
     - Executar o comando `cat /etc/os-release` no container `01container` sem se acoplar a ele.
     - Reover o container `01container` que está em andamento.
     - Fazer o download da imagem `nginx` com a versão `1.21.3-alpine` sem criar ou rodar um container.
     - Rodar um novo container com a imagem  `nginx` com a versão `1.21.3-alpine` em segundo plano nomeando-o como `02images` e mapeando sua porta padrão de acesso para porta `3000` do sistema hospedeiro.
     - Parar o container `02images` que está em andamento.
     - Gerar uma build a partir do Dockerfile do `back-end` do `todo-app` nomeando a imagem para `todobackend`.
     - Gerar uma build a partir do Dockerfile do `front-end` do `todo-app` nomeando a imagem para `todofrontend`.
     - Gerar uma build a partir do Dockerfile dos `testes` do `todo-app` nomeando a imagem para `todotests`.
     

