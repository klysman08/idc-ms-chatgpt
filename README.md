# Projeto de Chat com Keycloak

Este projeto é uma aplicação de chat que utiliza o Keycloak como provedor de autenticação. Ele consiste em duas partes: o serviço de chat e a aplicação web.

## Instalação

Para instalar o projeto, siga os seguintes passos:

- Construir a imagem docker da aplicação chatservice
- Aplicar o manifesto do chatservice
- Aplicar o manifesto do Keycloak 
- Alterar o arquivo host da máquina para adicionar o host keycloak 
- Construir a imagem docker da aplicação webapp
- Aplicar o manifesto da aplicação webapp

## Uso

Para usar o projeto, siga os seguintes passos:

- Inicie o serviço de chat
- Inicie a aplicação web
- Acesse a aplicação web em um navegador

## Serviços utilizados

Este projeto utiliza os seguintes serviços:

- **GitHub Actions**: para automatizar o processo de build e deploy das aplicações.
- **Kubernetes**: para orquestrar os containers das aplicações.
- **AWS**: como provedor de aplicação em nuvem.

## Links úteis

- [DBeaver](https://dbeaver.io/download/)
- [Plataforma da OpenAI](https://platform.openai.com/)
- [Postman](https://www.postman.com/)