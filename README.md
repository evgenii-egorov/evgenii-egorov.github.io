# Evgenii Egorov personal site

Academic personal site in the style of Kirill Neklyudov's Hugo Book homepage.

The root `index.html` is a static preview that works immediately on GitHub Pages.
The Hugo Book source is also included:

- `hugo.yaml`
- `content/_index.md`
- `content/personal.md`
- `content/*.jpg`
- `themes/hugo-book/`

To rebuild the static site into `public/` and refresh the root files used by GitHub Pages:

```bash
hugo --minify --cleanDestinationDir
cp -R public/. .
```
