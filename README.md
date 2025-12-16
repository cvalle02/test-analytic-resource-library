# Resource Hub (GitHub Pages + Jekyll + Minimal Mistakes)

This repository is a lightweight **resource hub** (no data stored) built with:
- GitHub Pages
- Jekyll
- Minimal Mistakes (remote theme)

## 1) Publish on GitHub Pages (no local setup required)

1. Create a GitHub repo (public is simplest).
2. Upload the contents of this folder to the **root** of the repo.
3. In GitHub: **Settings → Pages**
   - **Build and deployment**: "Deploy from a branch"
   - **Branch**: `main` / `(root)`
4. Wait for Pages to build, then open the URL shown in Settings → Pages.

## 2) Edit content

- Landing page: `index.md`
- Section pages: files in `_pages/`
- Top navigation: `_data/navigation.yml`

## 3) Add links to files / videos

Edit the section pages in `_pages/` and add Markdown links, e.g.
- [Download the data dictionary (PDF)](https://example.org/file.pdf)
- [Mentioned tutorial video](https://youtube.com/...)

## Notes
- This uses `remote_theme: mmistakes/minimal-mistakes` (supported by GitHub Pages for remote themes).
- Minimal Mistakes uses `jekyll-include-cache`; it is listed in `_config.yml` plugins.
