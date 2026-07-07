# FCAM OS Development Rules


# Código

Seguir:

- Clean Code
- SOLID
- DRY
- KISS


# Organização

Separar:

- Domain
- Application
- Infrastructure
- Presentation


# Banco

Nunca criar alteração manual.

Sempre utilizar migrations.


# API

Controllers devem ser simples.

Regras ficam em Services/UseCases.


# Frontend

Componentes devem ser reutilizáveis.

Não colocar regra de negócio dentro da interface.


# Commits

Utilizar:

feat:
nova funcionalidade

fix:
correção

docs:
documentação

refactor:
melhoria

chore:
configuração


# Segurança

Todas as ações devem validar permissão.

Nunca confiar apenas no frontend.