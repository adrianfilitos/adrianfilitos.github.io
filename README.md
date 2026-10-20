# adrianfilitos.github.io

Personal site for **Nixer (adrianfilitos)**.

- `index.html` — landing page with the short bio and selected projects.
- `about.html` — longer profile, projects and FAQ, with `Person` structured data.
- `styles.css` — dark theme, no dependencies.
- `robots.txt` and `sitemap.xml` — for crawlers.

Served by GitHub Pages from the `main` branch root.

## Edit

Change the HTML directly, commit and push. Pages rebuilds in about a minute.

After publishing the `oc-notify` package on npm, add the npm profile to the
`sameAs` array in both JSON-LD blocks:

```json
"sameAs": [
  "https://github.com/adrianfilitos",
  "https://www.npmjs.com/~adrianfilitos"
]
```
