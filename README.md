# Liquid Pixel Font

Editor de fontes pixeladas com controles globais de liquidez, preview de texto e exports SVG/OTF.

## Publicação

O workflow `.github/workflows/pages.yml` publica a pasta `dist` no GitHub Pages a cada push na branch `main`. Também pode ser executado manualmente em Actions.

## Desenvolvimento local

Execute `python -m http.server 8000 --directory dist` e abra http://localhost:8000.

Os desenhos são salvos no localStorage do navegador. Não há backend nem dependências de build.
