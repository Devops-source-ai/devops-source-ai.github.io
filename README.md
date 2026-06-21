# Portfolio Website

This is a static portfolio website that can be published with GitHub Pages.

## Customize

Edit these files:

- `index.html` for your name, project text, email, and GitHub links.
- `styles.css` for colors, spacing, and layout.
- `script.js` for small interactive behavior.

Replace these placeholders before publishing:

- `your.email@example.com`
- `https://github.com/devops-source-ai` if you want to link directly to a project instead.
- `https://www.instagram.com/devops.source/` if you want to change the Instagram page.
- Sample project titles, descriptions, and GitHub links.

## Publish With GitHub Pages

1. Create a new repository on GitHub.
2. Upload `index.html`, `styles.css`, `script.js`, and this `README.md` to the repository root.
3. Open the repository settings.
4. Go to `Pages`.
5. Set `Source` to `Deploy from a branch`.
6. Choose the `main` branch and `/root`.
7. Save. GitHub will give you a public website URL.

If you use Git locally:

```bash
git init
git add .
git commit -m "Add portfolio website"
git branch -M main
git remote add origin https://github.com/devops-source-ai/devops-source-ai.github.io.git
git push -u origin main
```

Your GitHub Pages URL should be:

```text
https://devops-source-ai.github.io/
```
