# Contexto operacional do Codex

Esta pasta contém contexto versionável do repositório **git-competeti**.

## O que o Codex carrega

- `AGENTS.md` é a entrada de instruções do repositório.
- Os demais arquivos desta pasta são convenções do projeto e são lidos por demanda através de `CONTEXT_INDEX.md`.
- `MEMORY.md` é memória editorial controlada; não é o armazenamento automático de memórias do Codex.

## Configuração deliberadamente ausente

Não há `.codex/config.toml`, regras, hooks, MCP ou agentes personalizados neste bootstrap. A configuração global permanece em `C:\Users\bfmano\.codex`. Recursos por projeto só devem ser adicionados quando houver ganho concreto, compatibilidade confirmada e responsável de manutenção.

`PLANS.md` não foi criado: para o estágio atual, `templates/TASK.md` cobre o planejamento necessário. Projetos longos podem adotá-lo depois.

## Fluxo

1. Leia `CONTEXT_INDEX.md`.
2. Use `templates/TASK.md` para trabalho com várias etapas.
3. Atualize `CURRENT.md` durante o trabalho.
4. Registre decisões duráveis em `DECISIONS.md`.
5. Registre somente fatos reutilizáveis em `MEMORY.md`.

Referências oficiais: [AGENTS.md](https://learn.chatgpt.com/docs/agent-configuration/agents-md) e [configuração por projeto](https://learn.chatgpt.com/docs/config-file/config-basic).
