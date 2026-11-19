# Polimorphic Help Center

Public help docs and changelog for Polimorphic, published with [Mintlify](https://mintlify.com).

## Editing

- **In the browser:** use the Mintlify web editor. Saving opens a pull request for review.
- **Locally:** install the CLI (`npm i -g mint`, Node 20.17+) and run `mint dev` to preview at http://localhost:3000.

Before merging, run:

```bash
mint validate
mint broken-links
```

## Layout

| Path | What it is |
|---|---|
| `docs.json` | Site settings: navigation, colors, logo, navbar, footer |
| `index.mdx` | Home page |
| `changelog.mdx` | Weekly release notes, one `<Update>` block per week (newest first) |
| `<topic>/…/*.mdx` | Help articles, grouped by topic |
| `images/articles/` | Article screenshots and diagrams |
| `logo/`, `favicon.png` | Branding |

New pages only show in the sidebar after they are added to `navigation` in `docs.json`.
