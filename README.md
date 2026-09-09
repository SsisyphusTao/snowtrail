# Snowtrail preview

A small, static introduction to Snowtrail for sharing on LinkedIn.

Public URL: https://ssisyphustao.github.io/snowtrail-preview/

The HTML, Open Graph image, and favicon are served by GitHub Pages. Browsers immediately redirect to the original Cloudflare-hosted experience using `window.location.replace`. The Open Snowtrail button remains available when JavaScript is disabled. Crawlers that do not execute JavaScript can read the static share metadata; LinkedIn compatibility must be verified separately.

## Publishing

GitHub Pages serves the root of the `gh-pages` branch. Publish changes with:

```sh
git push origin main
git push origin main:gh-pages
```

In repository Settings → Pages, the source is Deploy from a branch, `gh-pages`, `/ (root)`.

## Verification

Check the public page and `assets/preview.png` return HTTP 200. Use LinkedIn Post Inspector with the public URL, then add that URL through LinkedIn Add media. A working Pages deployment alone does not confirm LinkedIn import success.
