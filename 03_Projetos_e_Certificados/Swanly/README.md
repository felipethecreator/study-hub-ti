# Swanly

Backend de um projeto de rede social inspirado no Twitter/X, desenvolvido por Felipe Rodrigues Queiroz. O código público atual concentra-se no gerenciamento de usuários.

## Objetivo

Construir uma API para uma plataforma de mensagens curtas. O README original descreve a proposta de usuários, postagens e interações sociais; o módulo de usuários constitui a implementação encontrada nesta revisão.

## Tecnologias

- Node.js e TypeScript.
- Express para rotas HTTP.
- MongoDB e Mongoose para armazenamento e modelagem de dados.
- bcrypt para geração de hashes de senha.
- express-validator para validação de entradas.
- dotenv, ts-node e nodemon no ambiente de desenvolvimento.

## Funcionalidades verificadas no código

- Cadastro de usuários pela rota `/register` do módulo de usuários.
- Consulta e exclusão de usuários por identificador.
- Geração de hash da senha antes de armazenar o usuário.
- Middleware de validação de nome de usuário.
- Separação do código em rotas, controllers, services e model.

## Escopo atual

Postagens, curtidas, comentários e autenticação por login são parte da proposta descrita ou esperada para a rede social, mas não foram encontrados implementados no código consultado. Por isso, não são apresentados como funcionalidades prontas. O script `test` do `package.json` também informa que não há testes configurados.

## Relevância para a formação

O projeto oferece prática com uma API em TypeScript, organização em camadas, operações em MongoDB, validação de dados e armazenamento de senhas com hash.

## Código e documentação original

- [Repositório Swanly Backend](https://github.com/felipethecreator/Swanly-backend)
- [README com a proposta do projeto](https://github.com/felipethecreator/Swanly-backend/blob/main/README.md)
- [Dependências e comandos do projeto](https://github.com/felipethecreator/Swanly-backend/blob/main/package.json)
- [Rotas de usuários](https://github.com/felipethecreator/Swanly-backend/blob/main/src/routes/userRoutes.ts)
- [Serviço de usuários](https://github.com/felipethecreator/Swanly-backend/blob/main/src/service/userService.ts)

Esta pasta documenta o projeto no Study Hub. O código e as configurações permanecem no repositório original. As funcionalidades foram identificadas pela leitura do código; a API não foi executada nesta revisão.

[Voltar aos projetos](../README.md) · [Voltar ao Study Hub](../../README.md)
