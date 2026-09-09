# Aref Einizade — academic website

This is a Quarto-based academic website adapted for Aref Einizade from the provided Jhony H. Giraldo website codebase. The visual system, responsive layout, navigation, search, publication rendering, news rendering, team cards, teaching cards, SEO metadata, and GitHub Pages workflow are preserved, while identity and academic content have been replaced with Aref Einizade's public information.

## Local preview

```bash
python3 scripts/render_content.py --check
quarto preview
```

## Build

```bash
python3 scripts/render_content.py
quarto render
```

The website is configured for `https://arefeinizade.github.io`.
