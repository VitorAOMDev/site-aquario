# SEO — Atividade 2

## Palavras-chave escolhidas
1. peixes de aquário
2. aquário para iniciantes
3. betta neon guppy

## Decisões tomadas
- **title e description:** cada página tem os seus, com as palavras-chave.
  - index.html: "Peixes de Aquário para Iniciantes: Betta, Neon e Guppy"
  - sobre.html: "Como Montar seu Primeiro Aquário: Sobre o Guia"
- **canonical e Open Graph:** em cada página, com URL completa. A imagem de compartilhamento é `imagens/capa.jpg` (1200×630).
- **favicon:** `favicon.svg`.
- **JSON-LD:** tipo `Article`, no `index.html`. Validado em validator.schema.org (print em `imagens/validacao-schema.png`).
- **robots.txt e sitemap.xml:** na raiz do repositório, com as 2 páginas.
- **URLs amigáveis:** `sobre.html`, em minúsculas e sem parâmetros.
- **Links internos:** com texto descritivo ("guia de peixes de aquário para iniciantes", "como montar seu primeiro aquário"), e não "clique aqui".
- **Imagens:** convertidas para WebP, com `alt`, `width` e `height`. As duas últimas usam `loading="lazy"`.

## Lighthouse (celular)

| Categoria      | Antes | Depois |
|----------------|-------|--------|
| Desempenho     |       |        |
| Acessibilidade |       |        |
| Boas práticas  |       |        |
| SEO            |       |        |

Prints: `imagens/lighthouse-antes.png` e `imagens/lighthouse-depois.png`
