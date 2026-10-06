# tufava (PWA)

Site estático instalável (PWA), sem build. Arquivos:

- `index.html`: o site completo
- `manifest.webmanifest`: nome, cores e ícones do app
- `sw.js`: service worker (funciona offline depois da primeira visita)
- `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png`, `favicon.ico`, `favicon.svg`, `favicon-32.png`: ícones (ficam na raiz, sem pasta)

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo `tufava`).
2. Envie TODOS os arquivos deste ZIP para a raiz do repositório (todos juntos, sem pastas).
3. Vá em Settings > Pages, escolha Deploy from a branch, branch `main`, pasta `/ (root)`, e salve.
4. Abra `https://SEU-USUARIO.github.io/tufava/` (precisa ser HTTPS, o GitHub Pages já é).

## Instalar no celular

- iPhone (Safari): Compartilhar > Adicionar à Tela de Início.
- Android (Chrome): menu ⋮ > Instalar app (ou Adicionar à tela inicial).

## Atualizar o site

Depois de editar o `index.html`, aumente o número em `VERSION` no `sw.js` (por exemplo `tufava-v2`) para os usuários receberem a versão nova.
