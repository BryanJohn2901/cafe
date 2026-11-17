# Café Aurora (site fictício)

Site estático simples de uma cafeteria fictícia, com página inicial e blog. Feito para testes.

## Estrutura

- `index.html`: página inicial
- `blog/index.html`: lista de posts
- `blog/*.html`: um arquivo por post
- `assets/style.css`: estilos

## Rodar localmente

Abra `index.html` no navegador, ou:

```bash
python3 -m http.server 8080
```

## Novo post

Copie um arquivo de `blog/`, troque título, data e texto, e adicione o link em `blog/index.html` e em `index.html`.
