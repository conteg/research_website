# Giorgia Conte — refreshed academic website

A dependency-free, responsive site for GitHub Pages. The publishable files are in `docs/`. Open `docs/index.html` directly to preview, or serve this folder with any static HTTP server.

## Publish from the existing repository

1. Merge the redesign branch into `master` after reviewing it.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose **master** and **/docs**, then save.
5. GitHub displays the published URL when deployment finishes. With the current repository name, the expected URL is `https://conteg.github.io/research_website/`.

The previous Academic Pages template remains outside `docs/` and is not used by this publishing configuration. No Ruby, Node, or package installation is needed.

## Make updates

- Biography, papers, links, upcoming position, and contact: edit `docs/index.html`.
- Colors, spacing, typography, and mobile layout: edit `docs/style.css`.
- Photo: replace `docs/portrait.jpg`.
- CV: replace `docs/files/CV_Conte.pdf` using the same filename.

The CV is hosted in `docs/files/CV_Conte.pdf`; the three supplied paper drafts and Gray Parade slides are hosted alongside it in `docs/files/`. The existing Gray Parade paper link is retained separately. Check the collaborators’ names and affiliations before publication; these were carried over from the current website. The existing three full abstracts are preserved; the education–fertility abstract is reproduced from the supplied paper. Titles match the supplied documents.

## Custom domain

First confirm that the GitHub Pages URL works. Then follow GitHub's custom-domain instructions to verify ownership, set the custom domain in Pages settings, and update DNS at the domain provider. Do not change DNS until the new site is ready. This draft does not change `www.giorgia-conte.com`, add a CNAME file, or alter the current Google Sites website.

Official documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

Content source: https://www.giorgia-conte.com/about and https://www.giorgia-conte.com/research (reviewed 10 November 2026).
