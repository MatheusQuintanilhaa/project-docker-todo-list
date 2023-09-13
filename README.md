# Project Docker To-Do List

Este é um projeto de exemplo que demonstra como criar e executar uma aplicação To-Do List em um ambiente Dockerizado. Este repositório contém os arquivos necessários para construir e implantar a aplicação em um contêiner Docker.

## Pré-requisitos

Antes de começar, certifique-se de que você tenha o Docker instalado em seu sistema. Você pode encontrar instruções de instalação do Docker [aqui](https://docs.docker.com/get-docker/).

## Configuração

1. Clone este repositório em sua máquina local:

   ```bash
   git clone https://github.com/MatheusQuintanilhaa/project-docker-todo-list.git

2. Navegue até o diretório do projeto:
    ```bash
    cd project-docker-todo-list

3. Execute o seguinte comando para criar uma imagem Docker do aplicativo:
   ```bash
    docker build -t todo-list-app .

4. Inicie um contêiner Docker com o aplicativo:
   ```bash
    docker run -d -p 8080:80 todo-list-app

5. Acesse a aplicação em seu navegador web:

    http://localhost:8080
