# Publicacao no Cloudflare Pages

Este guia descreve o caminho recomendado para publicar o site institucional da XWCore no Cloudflare Pages.

## Modelo Recomendado

Usar a integracao GitHub + Cloudflare Pages.

Neste modelo, o Cloudflare acessa o repositorio `xwcore-oficial/xwcore-site` e publica automaticamente toda vez que houver um `push` na branch `main`.

Nao e necessario SSH, servidor VPS ou envio manual de arquivos.

## Repositorio

- Organizacao GitHub: `xwcore-oficial`
- Repositorio: `xwcore-site`
- Branch de producao: `main`
- Pasta publicada: `site`

## Configuracao no Cloudflare

1. Acesse o painel do Cloudflare.
2. Entre em **Workers & Pages**.
3. Clique em **Create application** ou **Create**.
4. Escolha **Pages**.
5. Escolha **Connect to Git**.
6. Autorize o Cloudflare a acessar o GitHub.
7. Selecione a organizacao `xwcore-oficial`.
8. Selecione o repositorio `xwcore-site`.
9. Use estas configuracoes:

| Campo | Valor |
| --- | --- |
| Project name | `xwcore-site` |
| Production branch | `main` |
| Framework preset | `None` |
| Build command | vazio |
| Build output directory | `site` |
| Root directory | vazio ou raiz do repositorio |

10. Clique em **Save and Deploy**.

## Dominio Personalizado

Depois do primeiro deploy:

1. Abra o projeto no Cloudflare Pages.
2. Entre em **Custom domains**.
3. Adicione `xwcore.com`.
4. Adicione tambem `www.xwcore.com`, se desejar.
5. Configure `xwcore.com.br` para redirecionar ou apontar para o mesmo site.

## Observacoes

- O arquivo `site/CNAME` existe para compatibilidade com GitHub Pages, mas o Cloudflare Pages nao depende dele.
- O dominio `xwcore.com` ja esta no Cloudflare, entao o vinculo com Pages tende a ser mais simples.
- O repositorio e publico, mas o Cloudflare tambem funciona com repositorios privados caso a permissao seja concedida.

## Alternativa por Token/API

Tambem e possivel publicar via Wrangler/API usando um token do Cloudflare, mas esse caminho so deve ser usado se a integracao com GitHub nao for desejada.

Se for necessario usar token, ele deve ser criado no Cloudflare com permissao de edicao para Cloudflare Pages e configurado localmente como variavel de ambiente. Nunca cole token, senha ou chave de API em conversas.

