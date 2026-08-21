# Índice de contexto

## Leitura mínima

1. [PROJECT.md](PROJECT.md) — objetivo, escopo e stack verificada.
2. [CURRENT.md](CURRENT.md) — estado transitório, pendências e trabalho atual.
3. Consulte os documentos abaixo conforme a tarefa.

| Documento | Uso | Quando ler |
|---|---|---|
| [MEMORY.md](MEMORY.md) | Fatos duráveis e confirmados | Ao retomar contexto |
| [DECISIONS.md](DECISIONS.md) | Decisões e consequências | Antes de mudar arquitetura ou processo |
| [STANDARDS.md](STANDARDS.md) | Padrões de engenharia e conteúdo | Antes de implementar ou revisar |
| [GIT_WORKFLOW.md](GIT_WORKFLOW.md) | Branches, commits e promoção | Antes de operar Git |
| [SECURITY.md](SECURITY.md) | Segredos, dados e ações sensíveis | Em qualquer tarefa com risco |
| [README.md](README.md) | Funcionamento desta estrutura | Ao manter a governança |
| [../README.md](../README.md) | Conteúdo público do perfil | Em qualquer mudança editorial |

## Templates

- [TASK.md](templates/TASK.md) — tarefa com escopo, plano e critérios.
- [DECISION.md](templates/DECISION.md) — nova decisão arquitetural ou operacional.
- [HANDOFF.md](templates/HANDOFF.md) — transferência de contexto.

## Cadência

- Atualize `CURRENT.md` sempre que o estado de trabalho mudar.
- Atualize `DECISIONS.md` somente quando houver decisão durável.
- Atualize `MEMORY.md` quando um fato confirmado reduzir releitura futura.
- Evite copiar logs, diffs extensos ou o conteúdo do README.
