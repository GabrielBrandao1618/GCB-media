# GCB media

Projeto criado com o intúito de criar uma rede social simples

## Tecnologias utilizadas

* React.js + Next.js
* MySQL
* Styled components
* Typescript
* Radix-ui
___
## Esquema de tabelas

### tbusers
Atributo | Tipo | Exemplo
-|-|-
userId | INT | 12
userName | VARCHAR(40) | Gabriel
userPassword | VARCHAR(20) | 12345678

### tbpost
Atributo | Tipo | Exemplo
-|-|-
postId | INT | 10
userId | INT | 12
imageUrl | VARCHAR(50) | https://github.com/GabrielBrandao13.png
datePost | datetime | 2021-12-06 16:50:08
text | VARCHAR(100) | Meu primeiro post

## Chaves estrangeiras

Tabela 1 | Tabela 2 | Coluna
-| -| -
tbusers | tbpost | userId
___
## Variáveis de ambiente

Campo | Descrição | Exemplo
-| -| -
BD_HOST | Servidor onde se localiza o banco de dados | localhost
BD_USER | Nome de um usuário do banco de dados | root
BD_PASS | Senha do usuário do banco de dados | 123456
BD_NAME | Nome do banco de dados | bdusers

