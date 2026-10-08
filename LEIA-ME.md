# Marcador de Truco (PWA)

## Publicar (grátis, 2 min)
Qualquer hospedagem estática com HTTPS serve:
- **Netlify Drop**: arraste esta pasta em https://app.netlify.com/drop
- **GitHub Pages**: suba a pasta num repositório e ative Pages
- **Vercel**: `npx vercel` dentro da pasta

## Instalar no celular
- **Android (Chrome)**: abra o link → menu ⋮ → *Instalar app*
- **iPhone (Safari)**: abra o link → Compartilhar → *Adicionar à Tela de Início*

Funciona offline depois da primeira abertura.

## Música da vitória
Coloque um arquivo seu chamado `vitoria.mp3` nesta pasta (e adicione `'vitoria.mp3'`
na lista `ASSETS` do `sw.js` para tocar offline). Sem ele, toca uma fanfarra sintetizada.
