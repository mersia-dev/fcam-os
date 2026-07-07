# FCAM OS - Project Context

## Identificação

Nome:
FCAM OS

Versão:
0.0.1

Tipo:
Sistema de Gerenciamento de Ordens de Serviço

Status:
Em desenvolvimento


# Objetivo

O FCAM OS é uma plataforma para gerenciamento completo de ordens de serviço técnicas.

O sistema deve controlar todo o ciclo operacional:

Solicitação
→ Planejamento
→ Execução
→ Registro técnico
→ Validação
→ Relatório
→ Encerramento


# Visão

Criar uma plataforma profissional, escalável e independente para empresas que trabalham com equipes técnicas em campo.


# Princípios

## Independência

O sistema não deve depender de plataformas proprietárias.

## Modularidade

Cada módulo deve possuir responsabilidade única.

## Escalabilidade

A arquitetura deve permitir evolução contínua.

## Auditoria

Eventos importantes devem possuir histórico.


# Domínio Principal

A entidade central do sistema é:

Work Order (Ordem de Serviço)


Uma Ordem de Serviço possui:

- Cliente
- Local
- Solicitante
- Técnico(s)
- Equipe
- Prioridade
- Status
- Histórico
- Fotos
- Relatório
- Tempo de execução


# Usuários

Perfis:

ADMIN

Gerenciamento completo.


SUPERVISOR

Coordenação operacional.


TECH

Execução técnica.


SOLICITANTE

Abertura e acompanhamento.


CLIENTE

Visualização e aprovação.


# Módulos

- Auth
- Users
- Roles
- Clients
- Locations
- Technicians
- Teams
- Work Orders
- Schedule
- Kanban
- Reports
- Dashboard
- Audit


# Regras

Toda funcionalidade deve ser documentada.

Toda alteração deve possuir histórico.

Toda regra de negócio deve existir fora da camada visual.

O banco deve possuir migrations.

Código deve ser versionado.