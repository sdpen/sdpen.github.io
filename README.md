# sdpen.github.io

Personal website for Serigne Daouda PENE (sdpen).

This repository contains a simple single-page personal website (index.html + style.css) and a publications BibTeX file (publications.bib).

What this commit adds

- README.md — this file (project overview and quick instructions).
- .github/workflows/deploy-pages.yml — GitHub Actions workflow to automatically publish the site to GitHub Pages when content is pushed to the `main` branch.

Preview locally

1. Clone the repo:
   git clone git@github.com:sdpen/sdpen.github.io.git
   cd sdpen.github.io

2. Open `index.html` in your browser, or run a local server:
   python3 -m http.server 8000
   then open http://localhost:8000

Publishing with GitHub Pages

- This repository includes a workflow (`.github/workflows/deploy-pages.yml`) that will publish the repository contents to GitHub Pages automatically when you push to `main`.
- The workflow uses the official `actions/upload-pages-artifact` and `actions/deploy-pages` actions and requires the repository to allow GitHub Actions. The workflow has permissions configured to write Pages.

Notes on visibility

- The repository is currently private. GitHub Pages behavior for private repositories varies by account/plan. If you want the site publicly available at `https://sdpen.github.io`, set the repository to *Public* in repository Settings → General → Change repository visibility, then wait a minute and the site will be available after the workflow runs.

Troubleshooting

- If the workflow does not run, make sure Actions are enabled for this repository (Settings → Actions → General).
- To view Pages configuration or disable/enable Pages manually, go to Settings → Pages in the repository.

Contact

If you want me to make further changes or push additional content (talks, courses, projects, clocks widget), tell me here and I will update the repo.