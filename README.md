# Subaru

A starter website for an acupuncture practice, built as a plain static site for GitHub Pages.

## Local preview

From the repository root, run:

```bash
python3 -m http.server 4173 --directory dist
```

Then open <http://localhost:4173>.

## Customize

The first pass uses working copy for the practice name, services, and contact address. Update the visible content and `mailto:` link in `dist/index.html`, then push to `main` to redeploy through GitHub Pages.
