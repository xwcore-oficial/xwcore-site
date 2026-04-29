# Prompt de Inicio e Sincronismo Kiit

Este arquivo existe apenas como atalho local. A fonte principal das regras e:

`D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md`

Use o mesmo prompt em qualquer situacao: chat novo, chat existente, Kiit1, Kiit, projeto atual ou outro projeto dentro de `D:\Dropbox\PROJETOS`.

## Prompt universal

```text
Leia e siga D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md.
Depois identifique o projeto em que estamos trabalhando.
Se existir AGENTS.md no projeto, leia e siga.
Se existir PROJECT_STATE.md, leia para entender o estado atual.
Se existir CHANGELOG.md, use para consultar historico detalhado quando necessario.
Antes de editar arquivos, verifique o estado do Git quando houver repositorio.
Atualize PROJECT_STATE.md e CHANGELOG.md quando houver mudancas relevantes.
```

## Observacao importante

Salvar instrucoes em arquivos compartilhados nao torna essas regras automaticamente ativas em qualquer novo chat.

Para qualquer chat usar essas regras, basta colar o prompt universal acima.
