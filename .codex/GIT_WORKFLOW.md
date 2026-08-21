# Workflow Git

## Repositório

- Conta: `git-competeti`.
- Branch principal: `main`.
- Desenvolvimento cotidiano: `develop`.
- Homologação: `homol`.

## Fluxo padrão

1. Atualize `develop`.
2. Crie uma branch temporária: `feature/*`, `fix/*`, `chore/*` ou `hotfix/*`.
3. Implemente e valide.
4. Integre em `develop`.
5. Promova `develop` para `homol`.
6. Após homologação, promova `homol` para `main`.

As promoções atuais podem ser diretas e deliberadas, sem Pull Request, conforme o padrão já documentado. Evite commits diretos em `homol` e `main`.

## Commits e releases

Use Conventional Commits: `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`, `ci:` e `security:`. Use Semantic Versioning quando o projeto tiver releases.

## Segurança operacional

- Verifique `git status`, branch e diff antes de preparar commit.
- Não use `git add .` sem revisar o escopo.
- Commit, push, merge, tag, criação ou remoção de branch exigem solicitação explícita do usuário.
- Não reescreva histórico compartilhado.

## Estado específico

O estado atual é uma exceção: somente `main` existe. Até decisão explícita, use branches temporárias a partir de `main` e não crie `develop` ou `homol` automaticamente.
