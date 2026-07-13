# Landing Page Miriam Gontijo - Deploy Vercel

Este pacote é uma landing page estática. Não precisa de build, framework ou instalação de dependências.

## Como subir no Vercel

1. Suba todos os arquivos desta pasta para um repositório no GitHub.
2. No Vercel, clique em "Add New Project" e importe o repositório.
3. Em "Framework Preset", escolha "Other".
4. Deixe "Build Command" vazio.
5. Deixe "Output Directory" vazio ou como `.`.
6. Publique.

## Arquivos obrigatórios

- `index.html`
- `styles.css`
- `script.js`
- `vercel.json`
- `assets/favicon.svg`
- `assets/miriam-hero.jpg`
- `assets/miriam-portrait-clean.jpg`
- `assets/miriam-studio.jpg`

Não altere a estrutura das pastas antes do deploy, porque o HTML referencia os assets em `assets/`.
