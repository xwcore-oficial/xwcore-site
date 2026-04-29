# Changelog Operacional da XWCore

Este arquivo registra os fatos relevantes do projeto, dificuldades encontradas, decisoes tomadas e solucoes aplicadas.

## 2026-04-29 15:21:35 -03:00

### Fatos ocorridos

- O usuario solicitou a criacao da pasta do novo projeto `XW-Copy` em `D:\Dropbox\PROJETOS`.
- O usuario informou que iniciara outro projeto no Codex.

### Dificuldades encontradas

- O projeto XW-Copy ainda nao possuia pasta propria nem arquivos operacionais para retomada em novo chat.

### Solucoes aplicadas

- Criada a pasta `D:\Dropbox\PROJETOS\XW-Copy`.
- Criados arquivos iniciais do projeto:
  - `AGENTS.md`
  - `PROJECT_STATE.md`
  - `CHANGELOG.md`
  - `README.md`
- Os arquivos foram preenchidos com estado inicial, pendencias e orientacoes para Kiit/Kiit1.

### Estado atual

- O XW-Copy esta pronto para ser aberto em novo chat do Codex usando o prompt universal definido em `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md`.

## 2026-04-29 15:19:21 -03:00

### Fatos ocorridos

- O usuario solicitou a inclusao de um novo projeto em andamento: `XW-Copy`, gerenciador de backup.

### Dificuldades encontradas

- A grade visual do site estava originalmente ajustada para quatro projetos.
- A documentacao institucional ainda nao contemplava backup/protecao de dados como linha de atuacao.

### Solucoes aplicadas

- Adicionado `XW-Copy` ao `README.md`.
- Adicionada secao completa do `XW-Copy` em `docs/04-projetos.md`.
- Atualizado `docs/03-planejamento-cronograma.md` para incluir a versao inicial do XW-Copy.
- Atualizado `docs/01-conceito-institucional.md` para incluir backup e protecao de dados.
- Atualizado o site institucional em `site/index.html` com novo card do XW-Copy.
- Ajustada a grade de projetos em `site/styles.css` para comportar cinco cards de forma responsiva.
- Atualizado `PROJECT_STATE.md` com a lista atual de projetos e pendencia de detalhar o escopo inicial do XW-Copy.

### Estado atual

- A XWCore passa a listar cinco projetos em andamento: Interfone IP Wi-Fi, Modulo RF Wi-Fi MQTT, MonitorNFE, DASN Simples Nacional e XW-Copy.

## 2026-04-29 15:10:05 -03:00

### Fatos ocorridos

- O usuario aprovou a criacao de uma estrutura central de modelos para novos projetos.
- Foi definido que novos projetos devem usar modelos a partir de `D:\Dropbox\PROJETOS\_MODELOS_CODEX`.

### Dificuldades encontradas

- Um novo projeto pode ainda nao possuir `AGENTS.md`, `PROJECT_STATE.md`, `CHANGELOG.md` ou `README.md`.
- Sem modelos, Kiit1 e Kiit teriam que recriar a estrutura manualmente a cada projeto.

### Solucoes aplicadas

- Criada a pasta compartilhada `D:\Dropbox\PROJETOS\_MODELOS_CODEX`.
- Criados modelos globais:
  - `AGENTS.template.md`
  - `PROJECT_STATE.template.md`
  - `CHANGELOG.template.md`
  - `README.template.md`
  - `README.md` explicativo da pasta de modelos.
- Atualizado `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` para orientar o uso dos modelos em novos projetos.

### Estado atual

- Novos projetos dentro de `D:\Dropbox\PROJETOS` devem copiar/adaptar os modelos de `_MODELOS_CODEX` quando ainda nao tiverem estrutura operacional.

## 2026-04-29 15:02:04 -03:00

### Fatos ocorridos

- O usuario observou que nao faz sentido manter quatro prompts separados se o objetivo e usar o mesmo procedimento em todos os chats e projetos.
- Foi definido que `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` deve conter o prompt universal e as regras para todas as situacoes.

### Dificuldades encontradas

- A existencia de varios prompts poderia gerar duvida sobre qual usar.
- O arquivo `PROMPTS_DE_INICIO.md` duplicava regras que deveriam estar centralizadas no arquivo global.

### Solucoes aplicadas

- Adicionado um prompt universal em `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md`.
- Simplificado `PROMPTS_DE_INICIO.md` para ser apenas um atalho local que replica o prompt universal.
- Atualizados `PROJECT_STATE.md` e `AGENTS.md` para apontar para o prompt universal como fonte principal.

### Estado atual

- Em qualquer chat, novo ou existente, basta usar o prompt universal que manda ler `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md`.
- O arquivo global passou a ser a fonte central do sincronismo entre Kiit1 e Kiit.

## 2026-04-29 14:54:31 -03:00

### Fatos ocorridos

- O usuario solicitou um arquivo com prompts prontos para iniciar novos chats ou ativar sincronismo em chats existentes.
- O usuario perguntou se, ao informar "salvar para outros projetos", a regra fica automaticamente aberta para qualquer chat novo.

### Dificuldades encontradas

- As regras salvas em arquivos compartilhados nao sao ativadas automaticamente em novos chats.
- Um novo chat precisa receber uma instrucao inicial para ler os arquivos compartilhados e locais do projeto.

### Solucoes aplicadas

- Criado `PROMPTS_DE_INICIO.md` com textos prontos para Kiit1, Kiit, chats existentes, novos projetos e registro de decisoes.
- Atualizado `PROJECT_STATE.md`, `AGENTS.md` e `README.md` para referenciar `PROMPTS_DE_INICIO.md`.

### Estado atual

- Para ativar o sincronismo em qualquer chat novo, o usuario deve usar um dos prompts de `PROMPTS_DE_INICIO.md`.
- As regras gerais continuam salvas em `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` e dependem de leitura explicita pelo chat.

## 2026-04-29 14:48:13 -03:00

### Fatos ocorridos

- O usuario perguntou se a retomada entre Kiit1 e Kiit poderia usar um arquivo `PROJECT_STATE.md` em vez de depender apenas de ler instrucoes e changelog.
- Foi definido que `PROJECT_STATE.md` sera o resumo rapido do estado atual do projeto.

### Dificuldades encontradas

- O historico de chat nao sincroniza automaticamente entre computadores.
- O `CHANGELOG.md` e completo, mas pode ficar longo para retomada rapida.

### Solucoes aplicadas

- Criado `PROJECT_STATE.md` com resumo atual, links principais, infraestrutura, pendencias imediatas e protocolo de retomada.
- Atualizado `AGENTS.md` para exigir manutencao de `PROJECT_STATE.md`.
- Atualizado `README.md` para indicar a diferenca entre changelog operacional e estado atual resumido.

### Estado atual

- Kiit1 e Kiit devem usar `PROJECT_STATE.md` para retomada rapida e `CHANGELOG.md` para historico detalhado.

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
