# Snowtrail preview

A small, static introduction to Snowtrail for sharing on LinkedIn.

Public URL: https://ssisyphustao.github.io/snowtrail-preview/

The HTML, Open Graph image, and favicon are served by GitHub Pages. The page has no JavaScript or automatic redirect. The Open Snowtrail button opens the original Cloudflare-hosted experience.

## Publishing

GitHub Pages serves the root of the `gh-pages` branch. Publish changes with:

```sh
git push origin main
git push origin main:gh-pages
```

In repository Settings → Pages, the source is Deploy from a branch, `gh-pages`, `/ (root)`.

## Verification

Check the public page and `assets/preview.png` return HTTP 200. Use LinkedIn Post Inspector with the public URL, then add that URL through LinkedIn Add media. A working Pages deployment alone does not confirm LinkedIn import success.
