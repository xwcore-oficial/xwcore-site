# Domínios e Publicação

## Domínios

- `xwcore.com` registrado no Cloudflare.
- `xwcore.com.br` registrado no Registro.br.
- `github.com/xwcore` existe, mas a conta atual não possui permissão para criar repositórios nessa organização.
- `github.com/xwcore-oficial` é a organização oficial em uso.
- `github.com/xwcore-oficial/xwcore-site` é o repositório institucional inicial.

## Estratégia Recomendada

Usar `xwcore.com` como domínio principal internacional e `xwcore.com.br` como domínio local redirecionando para o principal ou servindo a mesma página institucional.

## Opções de Hospedagem

### Cloudflare Pages

Recomendado para a página institucional estática.

Vantagens:

- Integração direta com GitHub.
- CDN e SSL automáticos.
- Boa gestão de DNS no mesmo ambiente do domínio `.com`.
- Publicação simples a partir da pasta `site/`.

### GitHub Pages

Boa alternativa caso o repositório institucional seja público e a simplicidade seja prioridade.

Vantagens:

- Integração nativa com repositório.
- Fácil manutenção.
- Ideal para documentação aberta.

## Configuração Inicial Sugerida

- Repositório institucional: `xwcore-oficial/xwcore-site`.
- Pasta de publicação: `site/`.
- Branch de publicação: `main`.
- Domínio principal: `xwcore.com`.
- Redirecionamento: `www.xwcore.com` para `xwcore.com`.
- Domínio brasileiro: `xwcore.com.br` apontando ou redirecionando para `xwcore.com`.
