# Agência do Japa LP

Landing page institucional da **Agência do Japa**, criada para apresentar serviços digitais, portfólio, conteúdos e canais de contato em uma experiência estática pronta para GitHub Pages.

**Demo:** https://jovemegidio.github.io/AgenciadoJapa-LP/

![Agência do Japa](uploads/logo-1777550210245.png)

## Visão Geral

Este repositório contém uma página única em HTML, CSS e JavaScript puro, sem etapa de build. A estrutura foi pensada para publicação rápida, manutenção simples e boa apresentação pública no GitHub.

## Principais Recursos

- Hero institucional com chamada para conversão.
- Alternância entre tema escuro e claro.
- Seções de serviços, sobre, portfólio, depoimentos, blog e contato.
- Filtros interativos para portfólio e blog.
- Modal de artigos com fallback estático para funcionar no GitHub Pages.
- Botão flutuante de WhatsApp e formulário de contato demonstrativo.
- Metadados de SEO, Open Graph e Twitter Card.
- Workflow de deploy automático para GitHub Pages.

## Tecnologias

- HTML5
- CSS3
- JavaScript
- GitHub Pages
- GitHub Actions

## Estrutura

```text
.
├── .github/
│   ├── REPOSITORY_ABOUT.md
│   └── workflows/
│       └── pages.yml
├── uploads/
│   ├── logo-1777550186784.png
│   └── logo-1777550210245.png
├── .gitignore
├── .nojekyll
├── 404.html
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## Como Rodar Localmente

Como o projeto é estático, basta abrir o arquivo `index.html` no navegador.

Também é possível servir a pasta com um servidor local:

```bash
python -m http.server 8080
```

Depois acesse `http://localhost:8080`.

## Deploy

O deploy está configurado em `.github/workflows/pages.yml`.

Sempre que houver push na branch `main`, o GitHub Actions publica os arquivos estáticos no GitHub Pages usando o ambiente `github-pages`.

URL esperada da publicação:

```text
https://jovemegidio.github.io/AgenciadoJapa-LP/
```

## About Sugerido Para o GitHub

**Descrição:** Landing page institucional da Agência do Japa, agência digital focada em sites, apps, marketing e tecnologia.

**Website:** https://jovemegidio.github.io/AgenciadoJapa-LP/

**Tópicos:** `landing-page`, `agencia-digital`, `github-pages`, `html`, `css`, `javascript`, `marketing-digital`, `portfolio`

## Licença

Projeto proprietário da Agência do Japa. Todos os direitos reservados.
