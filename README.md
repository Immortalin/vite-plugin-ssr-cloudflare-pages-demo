# Vite-plugin-SSR Cloudflare Pages Streaming Demo

Demo of Vue 3 server-side rendering (SSR) with [vite-plugin-ssr](https://vite-plugin-ssr.com/) on Cloudflare Pages in streaming mode. Updated version of https://github.com/thetre97/vite-plugin-ssr-cloudflare-pages

## Run locally with miniflare
```
pnpm install 
pnpm run build
pnpx wrangler@beta pages dev ./dist/client/
```