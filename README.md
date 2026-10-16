# Mahesh Kulkarni — portfolio

Static personal site for [GitHub Pages](https://kulkarnimahesh321-boop.github.io/portfolio/).

Content is taken from the resume in this repo. All asset links are relative, so the site works at `/portfolio/`.

## Local preview

```bash
python3 -m http.server 8080
```

Open http://localhost:8080

## GitHub Pages

1. Push `main`.
2. In the GitHub repo: **Settings → Pages → Source → GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` publishes on every push to `main`.
