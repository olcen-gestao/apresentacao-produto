# Apresentação de produto

Slides públicos da apresentação de produto da Olcen.

## Desenvolvimento

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

O build gera os arquivos estáticos em `dist/`.

## Publicação

O workflow em `.github/workflows/deploy.yml` publica o deck no GitHub Pages a cada push na branch `main`.

Depois do primeiro push, habilite o GitHub Pages em:

```text
Settings > Pages > Build and deployment > Source: GitHub Actions
```
