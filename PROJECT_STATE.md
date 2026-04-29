# Estado Atual do Projeto XWCore

Ultima atualizacao: 2026-04-29 14:48:13 -03:00
Ultima revisao de sincronismo: 2026-04-29 15:19:21 -03:00

## Resumo

A XWCore possui base institucional, identidade visual inicial, site estatico, documentacao, repositorio GitHub oficial e publicacao inicial no Cloudflare Pages.

Projetos em andamento:

- Interfone IP Wi-Fi.
- Modulo RF Wi-Fi MQTT.
- MonitorNFE.
- DASN Simples Nacional.
- XW-Copy.

## Como Kiit1 e Kiit devem retomar este projeto

Ao iniciar uma nova conversa ou trocar de computador:

1. Ler `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md`.
2. Ler `AGENTS.md`.
3. Ler este `PROJECT_STATE.md`.
4. Consultar `CHANGELOG.md` quando precisar do historico detalhado.
5. Executar `git status --short --branch` antes de editar arquivos.

## Links principais

- GitHub: `https://github.com/xwcore-oficial/xwcore-site`
- Cloudflare Pages: projeto `xwcore-site`
- Site principal: `https://xwcore.com`
- Site com www: `https://www.xwcore.com`
- Modelos globais Codex/Kiit: `D:\Dropbox\PROJETOS\_MODELOS_CODEX`

## Estrutura atual

- `README.md`: visao geral do repositorio.
- `AGENTS.md`: instrucoes locais para Codex/Kiit.
- `CHANGELOG.md`: registro operacional cronologico.
- `PROJECT_STATE.md`: resumo rapido do estado atual.
- `PROMPTS_DE_INICIO.md`: atalho local com o prompt universal definido em `_INSTRUCOES_CODEX.md`.
- `docs/`: documentacao institucional, planejamento, publicacao e projetos.
- `site/`: site estatico publicado pelo Cloudflare Pages.

## Infraestrutura

- Organizacao GitHub: `xwcore-oficial`
- Repositorio: `xwcore-site`
- Branch principal: `main`
- Publicacao: Cloudflare Pages conectado ao GitHub.
- Pasta publicada: `site`
- `xwcore.com`: ativo com SSL.
- `www.xwcore.com`: ativo com SSL.
- `xwcore.com.br`: em transicao DNS no Registro.br para Cloudflare.
- Nameservers configurados para `xwcore.com.br`: `nico.ns.cloudflare.com` e `zelda.ns.cloudflare.com`.

## Pendencias imediatas

1. Aguardar propagacao DNS do `xwcore.com.br`.
2. Confirmar no Cloudflare quando `xwcore.com.br` mudar para ativo.
3. Adicionar `xwcore.com.br` nos dominios personalizados do Cloudflare Pages.
4. Adicionar `www.xwcore.com.br` nos dominios personalizados do Cloudflare Pages.
5. Verificar acesso HTTPS dos quatro dominios.
6. Detalhar escopo inicial do XW-Copy.

## Regras importantes

- Atualizar `PROJECT_STATE.md` quando o estado atual ou pendencias mudarem.
- Atualizar `CHANGELOG.md` ao concluir etapas, encontrar dificuldades ou tomar decisoes relevantes.
- Usar o prompt universal de `D:\Dropbox\PROJETOS\_INSTRUCOES_CODEX.md` em qualquer chat novo ou existente.
- Para novos projetos, usar os templates de `D:\Dropbox\PROJETOS\_MODELOS_CODEX`.
- Nao registrar credenciais, tokens, chaves ou senhas.
- Commitar e enviar alteracoes relevantes para o GitHub.
