# Nova LP Tasty Media

Landing page da Tasty Media (marketing de performance para restaurantes).

Site estático: tudo está em `public/index.html`, sem build.

## Ver localmente

```sh
open public/index.html
# ou
python3 -m http.server 8080 -d public
```

## Publicar

Hospedado no Cloudflare Workers (arquivos estáticos, projeto `nova-lp-tasty`):
https://nova-lp-tasty.pedrohvs-ads.workers.dev

```sh
npx wrangler deploy
```
