# Personal Mathematics Website

This is a starter academic website built with Quarto and intended for GitHub Pages.

## 1. Edit placeholders

Search the project for these placeholders and replace them:

- `YOUR-GITHUB-USERNAME`
- `YOUR-ACADEMIC-EMAIL`

Review all biographical and academic details before publishing.

## 2. Preview locally

Open a terminal in this folder and run:

```bash
quarto preview
```

Quarto will show a local preview and refresh it when you save changes. Stop the preview with `Ctrl+C`.

## 3. Render the website

```bash
quarto render
```

The rendered website will be created in the `docs/` folder.

## 4. Publish with GitHub Pages

1. Create a **public** repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
2. Upload the project files to the root of that repository. Include the `_quarto.yml`, `.qmd` files, `styles.css`, and the other project files. You can upload them through GitHub's website, or use Git if installed.
3. Run `quarto render` locally before publishing so the `docs/` folder exists and contains `index.html`.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/docs**, then save.
7. Wait a few minutes and visit `https://YOUR-GITHUB-USERNAME.github.io`.

If GitHub Pages does not offer `/docs` as a source, confirm that the repository contains the rendered `docs/index.html` and that the files are on the `main` branch.

## Updating the site

Edit the `.qmd` files, run `quarto render`, and commit/push the updated source and `docs/` folder to the repository.

## Mathematical notation

Quarto's HTML output supports LaTeX-style mathematics through MathJax. For example:

```markdown
$$
D : \\Gamma(S) \\longrightarrow \\Gamma(S).
$$
```
