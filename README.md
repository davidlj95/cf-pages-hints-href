# Cloudflare Pages early hints: `<base href>` issue minimal reproduction
This repository is a minimal reproduction for an issue with Cloudflare Pages early hints and `<base href>`. 

Issue: https://github.com/cloudflare/workers-sdk/issues/7181

Open:
 - `public/subdir/index.html` in a browser 
 - [Live site](https://cf-pages-hints-base.pages.dev/subdir/)
For a detailed explanation about the issue

To reproduce it, install dependencies and deploy to Cloudflare Pages the `public` assets directory:

```shell
pnpm install
pnpm run deploy
```
