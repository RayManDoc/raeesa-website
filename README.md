# Raeesa Manjoo-Docrat — personal website

Source for <https://raymandoc.github.io/raeesa-website/>, built with [Quarto](https://quarto.org).

- `main` branch: these source files (edit here)
- `gh-pages` branch: the built site that GitHub Pages serves (don't edit by hand)

## Pages

| File | Page |
|---|---|
| `index.qmd` | About (home) |
| `publications.qmd` | Publications |
| `funding.qmd` | Research funding |
| `teaching.qmd` | Teaching |
| `supervision.qmd` | Supervision |
| `talks.qmd` | Talks |
| `join.qmd` | Join / contact |
| `_quarto.yml` | Site settings and menu |
| `styles.scss` | Colours, fonts and layout |

Dated items (publications, grants, talks ...) all use the same block. Copy an existing one and edit it:

```markdown
::: entry
[2026]{.when}

::: what
**Title of the item**

[Journal or details]{.meta}
:::
:::
```

## Preview and publish

```bash
quarto preview
```

```bash
quarto publish gh-pages
```

Commit and push your changes to `main` as well, so the source stays backed up.
