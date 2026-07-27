# Introduction to AI with Python

This repository contains the notebook-based learning materials for the AI with
Python course and publishes them as a website with Quarto and GitHub Pages.

## Add a new session

1. Save the completed `.ipynb` file in the repository root.
2. Give the notebook a clear first-level heading, for example
   `# Session 3: NumPy Foundations`.
3. Check that the notebook contains no passwords, tokens, or private student
   information.
4. Commit and push the new notebook to the `main` branch.
5. GitHub Actions will rebuild the website automatically. The new notebook is
   included automatically in the Course Sessions navigation.

## Preview locally

Install Quarto, then run:

```bash
quarto preview
```

Open the local address printed by Quarto. Stop the preview with `Ctrl+C`.

## Publish

The workflow in `.github/workflows/publish.yml` renders the website after every
push to `main`. In the GitHub repository, open **Settings → Pages** and select
**GitHub Actions** as the source the first time the site is published.

The course website is:

<https://wlos.github.io/ai_with_python_course/>
