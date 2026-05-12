# PrimeCarYT OP2

Landing page estática PrimeCar para YouTube (Operação 2). Deploy via Vercel no push.

## Tracking
- Google Ads: `AW-18123712630`
- UTMify Pixel ID: `69f35e46ab1ce94ca9c69370`
- O `window.googlePixelId` deve sempre ser `69f35e46ab1ce94ca9c69370`
- Nunca remover o script `pixel-google.js` da UTMify

## Contexto
Pixel ID diferente do tapetevolucar — cada projeto tem seu próprio dashboard UTMify
ligado à sua própria conta Google Ads. Misturar os IDs faz os eventos irem para a
conta errada.

## Stack
HTML/CSS/JS estático. Sem build step. Editar `index.html` diretamente.

## Deploy
```
git add index.html
git commit -m "mensagem"
git push
```

## Campanhas ativas (Google Ads)
Acompanhar via UTMify MCP — usar `get_dashboard_summary` com o dashboard OP2.
