# Publishing Balanced OKRs

The repository contains a Markdown pamphlet, a ten-chapter book draft, and a bibliography. A GitHub Actions workflow builds a MkDocs site and deploys it to GitHub Pages on pushes to `main`.

## Initial setup (repository administrator)

1. Merge the manuscript PR into `main` after review.
2. Open **Settings → Pages** in the GitHub repository.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Open **Actions → Publish Balanced OKRs to GitHub Pages** and run the workflow if it has not run automatically.
5. Once the deployment succeeds, the expected project-site address is **https://godeke.github.io/balanced-okr/**. Verify it in the Pages settings before sharing.

The site is public. No custom domain is needed. The workflow uses MkDocs 1.6.1 and publishes the pamphlet, chapter navigation, and bibliography.

## Editorial workflow

Edit Markdown in `book/` and `pamphlet/` on a branch, open a PR, and merge after review. A successful push to `main` triggers publication. The website is generated; do not edit `site-content/` or `site-output/` manually.

## Limitations

This is a first draft, not a peer-reviewed publication. Verify references and add sourced case studies before calling it a final edition. GitHub Pages deployment requires repository settings and Actions permissions; adding the workflow alone does not prove that a public site is live.
