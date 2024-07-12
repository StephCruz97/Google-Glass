<h1 align="center">
  PicPay Desafio Backend Sênior
</h1>

Este projeto é uma solução desenvolvida em C# como resposta ao <a href="https://github.com/PicPay/picpay-desafio-backend?tab=readme-ov-file" target="_blank">desafio</a> proposto pela PicPay para uma vaga de desenvolvedor backend sênior. Foi inspirado na solução apresentada por <a href="https://github.com/giuliana-bezerra" target="_blank">Giuliana Silva Bezerra</a> em um <a href="https://youtu.be/YcuscoiIN14" target="_blank">vídeo</a>, adaptando-a para uma aplicação em C# e adicionando funcionalidades extras, como JWT e novas rotas.

## Descrição do Projeto

O objetivo deste projeto é criar uma versão simplificada do PicPay, uma plataforma de pagamentos digitais. Ele consiste em um sistema onde os usuários podem realizar transações financeiras entre si, tais como enviar e receber dinheiro.

## Funcionalidades Principais

- Cadastro de usuários
- Autenticação com JWT (JSON Web Tokens)
- Envio de dinheiro entre usuários
- Consulta de saldo
- Histórico de transações

## Tecnologias Utilizadas

- C# (.NET Core)
- Swagger
- JWT (JSON Web Tokens) para autenticação
- SQL Server banco de dados
- ASP.NET Core para criação das APIs RESTful

## Como Executar o Projeto

1. Certifique-se de ter o SDK do .NET Core instalado em sua máquina.
2. Clone este repositório em sua máquina local.
3. Navegue até o diretório do projeto.
4. Configure a string de conexão com o banco de dados no arquivo appsettings.json.
5. Execute o comando dotnet restore para restaurar as dependências do projeto.
6. Execute o comando dotnet run para iniciar a aplicação.
7. Acesse as rotas da API conforme documentação para interagir com o sistema.

## Documentação da API
A documentação completa da API está disponível no arquivo picpay-desafio-backend.xml (vale ressaltar que também é possível acessá-la a partir do Swagger). Este documento descreve todas as rotas disponíveis, os parâmetros necessários e os retornos esperados.

## Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para reportar problemas ou propor melhorias. Se deseja contribuir com código, por favor abra um pull request explicando as alterações propostas.

## Autor
Este projeto foi desenvolvido por [João Guilherme F. Passos](https://github.com/JonnyYamagushi).
