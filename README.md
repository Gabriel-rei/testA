# app-staticsite

Site estático simples com duas páginas HTML modernas e responsivas.

## Visão geral

- `index.html`: página inicial com mensagem de boas-vindas e lista de ações (aprender, colaborar, compartilhar).
- `error.html`: página de erro amigável para exibir quando algo inesperado ocorre (pode ser usada como fallback 404/500 no host estático).

Ambas as páginas usam HTML5, tipografia Google Fonts (Roboto) e layout centralizado com cartão, sombras suaves e boa legibilidade.

## Personalização rápida

- Títulos e textos: edite diretamente os blocos de conteúdo em `index.html` e `error.html`.
- Cores e estilos: ajuste o bloco `<style>` em cada arquivo (paleta principal: azul `#1976d2`, cinzas neutros e vermelho de erro `#d32f2f`).
- Links do autor: atualize o link do LinkedIn conforme necessário.

## Dicas de implantação

Qualquer host de arquivos estáticos funciona (por exemplo, GitHub Pages, Nginx, S3, Azure Static Web Apps). Defina `index.html` como documento inicial e aponte `error.html` como página de erro, se o provedor suportar essa configuração.

## Licença

Este projeto é distribuído sob os termos da licença disponível em `LICENSE`.

## Autor

Kledson Basso — https://www.linkedin.com/in/kledsonbasso/