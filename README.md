<h1 align="center">Docker Todo List</h1>

# Sobre

Temos uma aplicação full-stack neste repositório, um aplicativo de tarefas! Esta aplicação foi conteinerizada para funcionar. Desenvolvendo os arquivos de configuração para cada frente específica: Front-end, Back-end e, no nosso caso, para um aplicativo de teste que valida se as aplicações estão se comunicando.

- Docker

# O que foi desenvolvido

- Conteinerização de aplicações;
- Criação de uma conexão entre elas;
- Orquestrar seu funcionamento.

# Features 

- [x] Cria container em modo interativo.
- [x] Inicia o container.
- [x] Lista os containers filtrando pelo nome.
- [x] Execute o comando `cat /etc/os-release` no container sem se acoplar a ele.
- [x] Remove o container.
- [x] Download da imagem `nginx`, sem criar ou rodar um container.
- [x] Roda novo container com a imagem `nginx`.
- [x] Para o container.
- [x] Gera uma build a partir do Dockerfile do back-end.
- [x] Gera uma build a partir do Dockerfile do front-end.
- [x] Gera uma build a partir do Dockerfile dos testes.
- [x] Orquestração em segundo plano com o docker-compose.
