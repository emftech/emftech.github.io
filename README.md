# Estefano Machado Ferrer — personal academic website

Jekyll site for GitHub Pages, in English (root) and Spanish (`es/`).

## Structure
- Pages: Home, Research, Projects, Teaching, News, Contact, CV. Each English page has a Spanish twin in `es/` with the same `ref` in its front matter; the EN/ES switch in the top bar uses `ref` to jump between them.
- Navigation and interface strings: `_data/i18n.yml`.
- News items (both languages): `_data/news.yml`. Add new items at the top.
- PDFs: `files/cv.pdf` (EN), `files/cv-es.pdf` (ES), `files/lauw2026-poster.pdf`, `files/machado-2026-thesis.pdf` (web-compressed; full resolution lives in the OCE_AcquisitionProtocols_Simulator repo).
- Design skills for future changes: `.claude/skills` (excluded from the build).

## Run locally
    gem install jekyll
    jekyll serve      # then open http://localhost:4000
