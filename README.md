
## Spring Security - Treinamento Prático

Repositório com um pequeno projeto para criação de um token para poder acessar um endpoint estando autentificado.

## Documentação da API

#### Retorna uma String

```http
  GET /api/v1/demo-controller
```

| Descrição                                                                                  |
|:-------------------------------------------------------------------------------------------|
| Retornar uma mensagem para o usuário que estiver autenticado, do contrário receber um 403. |

#### Retorna um Token

```http
  POST /api/v1/auth/register
```

| Corpo  | Descrição                                                                |
|:-------|:-------------------------------------------------------------------------|
| `User` | Registra no banco de dados um usuário e retornar um token como resposta. |

#### Retorna um Token

```http
  POST /api/v1/auth/authenticate
```

| Corpo  | Descrição                                                                                                  |
|:-------|:-----------------------------------------------------------------------------------------------------------|
| `User` | Busca no banco de dados um usuário com o email e senha passado no Corpo da requisição, e retorna um token. |



## Funcionalidades

- Autentificação de Usuário.
- Token.
- Mensagem de autentificação.

