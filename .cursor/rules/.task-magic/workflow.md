# Task Magic Workflow Guide

Este documento explica como usar o sistema Task Magic de forma eficiente no dia a dia.

## Fluxo de Trabalho Padrão

### 1. Iniciando um Novo Projeto/Feature
```
@.cursor/rules/.task-magic/plans.mdc create a plan for [feature name]
```

### 2. Criando Tarefas a partir de Planos
```
@.cursor/rules/.task-magic/tasks.mdc generate tasks for the [feature-name]-plan.md
```

### 3. Trabalhando em Tarefas
```
@.cursor/rules/.task-magic/tasks.mdc start working on task001
```

### 4. Arquivando Tarefas Concluídas
```
@.cursor/rules/.task-magic/memory.mdc archive completed task001
```

## Comandos Úteis

### Verificar Status do Projeto
```
@.ai/TASKS.md what is the current status of the project?
```

### Expandir Tarefas Complexas
```
@.cursor/rules/.task-magic/expand.mdc check if task001 needs to be expanded
```

### Consultar Histórico
```
@.ai/memory/ show me similar tasks from the past
```

## Boas Práticas

1. **Sempre começar com planos** antes de criar tarefas
2. **Manter TASKS.md atualizado** - é sua visão geral
3. **Arquivar tarefas concluídas** regularmente
4. **Consultar memória** antes de implementar algo novo
5. **Expandir tarefas grandes** em sub-tarefas menores

## Estrutura de Pastas Resultante

```
.ai/
├── TASKS.md              # Master task list
├── plans/
│   ├── PLAN.md          # Global project plan
│   └── features/        # Feature-specific plans
├── tasks/               # Active tasks
│   ├── task001_setup.md
│   └── task002_auth.md
└── memory/
    ├── TASKS_LOG.md     # Archived tasks log
    ├── PLANS_LOG.md     # Archived plans log
    ├── tasks/           # Archived task files
    └── plans/           # Archived plan files
``` 