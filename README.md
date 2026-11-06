# Hongwei (Alex) Wang — Academic Homepage

Source for the permanent academic homepage of Hongwei (Alex) Wang, built with the official [al-folio](https://github.com/alshedivat/al-folio) Jekyll starter.

The intended public repository is `hw4375-collab/hw4375-collab.github.io`, published at `https://hw4375-collab.github.io/`.

## Site structure

- `/_pages` — public pages and navigation
- `/_data/cv.yml` — rendered CV data
- `/_config.yml` — site identity, URL, and Jekyll configuration
- `/.github/workflows/deploy.yml` — GitHub Pages Actions deployment
- `MIGRATION_INVENTORY.md` — a local, non-published review inventory from the prior public homepage (intentionally ignored by Git)

The standard al-folio runtime remains in its versioned gems. The starter's example posts, projects, news, teaching, and book collections are excluded from the generated site until replaced by reviewed material.

## Local development

Prerequisites: Ruby/Bundler and Node.js 20 or later. ImageMagick is optional; it is only needed for responsive image generation when images are added.

```bash
bundle install
npm ci
bundle exec jekyll serve
```

Open `http://localhost:4000/`. The production-style local build is:

```bash
bundle exec jekyll build
```

Useful validation commands:

```bash
npm run lint:prettier
npm run lint:style-contract
bundle exec al-folio upgrade audit --no-fail
bundle exec jekyll build
```

## Publish to GitHub Pages

The `origin` remote is configured for `hw4375-collab/hw4375-collab.github.io`. Before the first release, confirm that the repository's Pages source is set to **GitHub Actions**.

1. From this directory, review the files to be committed and push the `main` branch. Do not use a blanket `git add .`, because the local migration inventory must remain private:

   ```bash
   git status
   git add <reviewed-public-files>
   git commit -m "Publish academic homepage"
   git push -u origin main
   ```

2. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source.
3. Open **Actions → Deploy GitHub Pages** and confirm the deployment completes. The website will be available at `https://hw4375-collab.github.io/`.

The workflow uses GitHub's official `upload-pages-artifact` and `deploy-pages` actions; no `gh-pages` branch is created or managed.

## Content checklist before publication

- Add a preferred academic contact address to `_data/socials.yml` and `_config.yml`.
- Add a current portrait in `assets/img/` only if one is wanted, remove `assets/img/` from `_config.yml`'s `exclude` list, then reference it in `_pages/about.md`.
- Replace the rendered CV's provisional record in `_data/cv.yml` with a reviewed academic CV, and add a PDF only when final.
- Review `MIGRATION_INVENTORY.md` item-by-item before moving historical entries into the public pages.
- Add publications only with confirmed authorship, dates, venue/preprint identifiers, and stable links.
