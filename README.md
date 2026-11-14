# oscar-gilg.github.io

Personal website for Oscar Gilg. Live at https://oscar-gilg.github.io.

Built with [Astro](https://astro.build/), starting from the [Astro Cactus](https://github.com/chrismwilliams/astro-cactus) template, then trimmed to a single page.

## Website text

The [canonical website text lives in Google Docs](https://docs.google.com/document/d/1YsgC89VyCHHJGNUPy-F8J_FRFkIlO-1SdW_0DPB1Aq0/edit).
Edit the **Website copy** tab first. Before changing website text here, read the
latest Doc, including suggestions and unresolved comments. The **Notes and
inspiration** tab is editorial material, not public website copy.

The Doc was seeded from this repository at `70f2144`; the deployed site was not
independently verified. Automatic syncing is not configured: publishing Doc
edits requires updating the site source and deploying it.

## Local development

```sh
npm install
npm run dev
```

Open http://localhost:4321 in your browser.

## Deployment

Pushes to `main` trigger the GitHub Actions workflow at `.github/workflows/deploy.yml`, which builds the site and deploys it to GitHub Pages.
