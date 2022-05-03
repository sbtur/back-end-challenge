# Back-end Challenge

## Notas gerais

- Não compartilhe seu teste publicamente em nenhuma plataforma durante o processo de seleção.
- Recomendamos que use um reposítório privado no Github e de acesso aos seguintes usuários: `silveiradasilvaa`, `mauriciors`, `MauSDJ` e `rafaelnogueira1`. (Em útimo caso, se tiver problemas em adicionar usuários em um repositório privado, deixe-o público e nos mande o link dele.)

## Nossas expectativas

Esperamos que seu trabalho reflita qualidade, extensividade e manutenibilidade, por isso sinta-se à vontade para mostrar isso ao desenvolver sua solução.

## Objetivo

Criar uma aplicação usando python/django que atenda os requisitos a seguir.

#### Tenha os seguintes end points:

- Listagem de todas as vitrines disponíveis
- Listagem de vitrines baseado em rotas

## Exemplos e/ou sugestões

#### Listagem de todas as vitrines

- URL: `/vitrines/`
- Retorno: [ver arquivo](files/all.js)

#### Listagem das vitrines para página `/`

- URL: `/vitrines/`
- Payload: {routes: ["/"]}
- Retorno: [ver arquivo](files/home.js)

#### Listagem das vitrines para página `/destinos`

- URL: `/vitrines/`
- Payload: {routes: ["/destinos"]}
- Retorno: [ver arquivo](files/destinos.js)

#### Listagem das vitrines para página `/sobre`

- URL: `/vitrines/`
- Payload: {routes: ["/sobre"]}
- Retorno: [ver arquivo](files/sobre.js)

## Informações adicionais

- Fique a vontade para criar mais dados para enriquecer o retorno da sua API, mas lembre-se, eles devem mater o formato solicitado.
- Você pode usar mocks baseado em arquivos, porém o uso de um banco de dados com certeza te colocará na frente.
- Foi solicitado apenas um tipo de "filtro" nos end points (o de `routes`), mas fique a vontade para criar mais além desse, por exemplo o de `limit` que limita a quantidade de `itens` dentro do retorno.
