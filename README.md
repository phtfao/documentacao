# Regras de Negócio

| **RN0001** |
|-----------|
| Esta regra se aplica a todos os usuários do sistema. |

| **RN0002** |
|-----------|
| Esta regra se aplica apenas a usuários administradores. |

| **RN0003** |
|-----------|
| Esta regra se aplica apenas a usuários autenticados. |

| **RN0004** |
|-----------|
| Esta regra se aplica apenas a usuários com mais de 18 anos. |

# História de Usuário: Cadastro de Usuário

Eu como usuário do sistema
Quero me cadastrar no sistema
Para ter acesso às funcionalidades exclusivas

## Critérios de Aceitação

- O usuário deve informar nome, email e senha
- O email deve ser único no sistema
- A senha deve ter no mínimo 8 caracteres
- O usuário deve concordar com os termos de uso do sistema (RN0001)
- O usuário deve ter mais de 18 anos (RN0004)
- O usuário deve receber um email de confirmação após o cadastro
