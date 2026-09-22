# Personal site — Divyansh Verma

Dark, single-page portfolio inspired by the classic developer layout: sticky side navigation, numbered sections, experience timeline, and expandable project cards.

## Run locally

No build step required. From this directory:

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Customize

- **Copy & roles:** Edit `index.html` (hero, experience, projects, contact email).
- **Colors & layout:** CSS variables at the top of `styles.css`.
- **Résumé:** Add `resume.pdf` at the repo root (linked from Experience).
- **LinkedIn:** Update the placeholder LinkedIn URL in `index.html`.

## Deploy to GitHub Pages

1. Commit and push to `main`.
2. In the repo on GitHub: **Settings → Pages → Build and deployment → Source:** Deploy from branch `main`, folder `/ (root)`.

Your site will be available at `https://divyanshvermapok15-star.github.io/divyanshvermapok15-star/` (or your custom domain if configured).

## Structure

| File         | Purpose                                      |
| ------------ | -------------------------------------------- |
| `index.html` | Sections: About, Experience, Projects, Contact |
| `styles.css` | Theme, layout, responsive sidebar            |
| `main.js`    | Active nav on scroll, project expand, mobile menu |
