# Music Review — Exercícios de Música (MSA e Órgão Eletrônico Vols. 1 a 4)

Aplicativo web progressivo (PWA) de revisão musical com questões organizadas por fases para o **MSA** e **Estudos para Órgão Eletrônico Aplicados ao Hinário (Volumes 1, 2, 3 e 4)**.

## Estrutura do app
- **MSA** — 500 questões em 16 fases.
- **Organista** — Estudos para Órgão Eletrônico, Volumes 1 a 4.
- **Músicos** — Métodos em PDF (Clarineta e Violino).

## Arquivos do Projeto
- `index.html` — Aplicação principal com banco completo de questões e exportação em PDF.
- `manifest.json` — Manifesto para instalação como aplicativo (PWA / Web App).
- `sw.js` — Service Worker para cache e funcionamento offline.
- `icon-192.png` e `icon-512.png` — Ícones do aplicativo.
- `metodo-para-clarineta-nabor-pires-camargo-pr.pdf` e `metodo-violino-lambert-pr.pdf` — PDFs da seção **Músicos** (devem ficar na mesma pasta do `index.html`).

## Publicação no GitHub Pages
1. Crie um repositório no GitHub (ex.: `music-review`).
2. Envie todos os arquivos (`index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, os dois PDFs e `README.md`) para a branch `main`.
3. No repositório, acesse **Settings** > **Pages**.
4. Em **Source**, selecione **Deploy from a branch**, escolha `main` e `/ (root)`, e clique em **Save**.
5. Acesse o endereço gerado (`https://seu-usuario.github.io/music-review/`).

## Instalação como Aplicativo (Web App / PWA)
- **Android (Chrome):** Abra o site, toque no menu **⋮** e selecione **Instalar aplicativo** (ou toque no botão **Instalar app** dentro da página).
- **iPhone / iPad (Safari):** Abra o site no Safari, toque em **Compartilhar** e escolha **Adicionar à Tela de Início**.
- **Computador (Chrome / Edge):** Clique no ícone de instalação na barra de endereços e confirme.
