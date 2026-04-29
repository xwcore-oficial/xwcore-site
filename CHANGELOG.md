# Changelog Operacional da XWCore

Este arquivo registra os fatos relevantes do projeto, dificuldades encontradas, decisoes tomadas e solucoes aplicadas.

## 2026-04-29 14:41:14 -03:00

### Fatos ocorridos

- O usuario perguntou se `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` pode ser acessado por outro computador com Codex.
- O usuario definiu os nomes operacionais `Kiit1` para este computador e `Kiit` para o outro computador.
- O usuario solicitou enriquecer a instrucao compartilhada para que o outro computador execute o mesmo protocolo e mantenha a mesma base de dados operacional.

### Dificuldades encontradas

- O arquivo compartilhado via Dropbox nao cria memoria automatica dentro do modelo; ele precisa ser lido no inicio dos trabalhos.
- A sincronizacao depende do Dropbox estar ativo e atualizado nos dois computadores.

### Solucoes aplicadas

- Enriquecido `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` com protocolo de inicio, sincronismo Kiit1/Kiit, regras de changelog, seguranca e referencias atuais do projeto XWCore.
- Registrado neste changelog o novo procedimento de continuidade operacional.

### Estado atual

- Kiit1 deve seguir `AGENTS.md` e manter este `CHANGELOG.md` atualizado.
- Kiit, ao acessar a mesma pasta sincronizada, deve ler `_INSTRUCOES_CODEX.md`, `AGENTS.md` e `CHANGELOG.md` antes de trabalhar.

## 2026-04-29 14:34:26 -03:00

### Fatos ocorridos

- Foi definida a necessidade de manter um registro operacional continuo do andamento dos trabalhos.
- O usuario solicitou que as informacoes sejam atualizadas conforme o progresso, incluindo dificuldades e solucoes.
- O usuario solicitou que essa preferencia fique salva para ser reutilizada em outros projetos.

### Dificuldades encontradas

- O projeto ainda nao possuia um arquivo formal para registrar historico operacional.
- A continuidade entre projetos depende de existir uma referencia persistente fora apenas da conversa atual.

### Solucoes aplicadas

- Criado este arquivo `CHANGELOG.md` na raiz do repositorio.
- Criado `AGENTS.md` com instrucao local para manter o changelog atualizado antes de finalizar etapas futuras.
- Criado arquivo compartilhado `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` para registrar a preferencia e permitir reutilizacao em outros projetos.

### Estado atual

- Repositorio oficial publicado em `https://github.com/xwcore-oficial/xwcore-site`.
- Site publicado no Cloudflare Pages.
- `xwcore.com` e `www.xwcore.com` ativos com SSL.
- `xwcore.com.br` em processo de delegacao DNS no Registro.br para os nameservers da Cloudflare `nico.ns.cloudflare.com` e `zelda.ns.cloudflare.com`.
