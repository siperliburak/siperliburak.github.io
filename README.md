# Burak Siperli — Academic Website

A custom Hugo academic website inspired by the modular structure of Favstats. It uses Markdown for content and a small custom CSS design rather than depending on a large theme.

## Local preview

1. Install Git and Hugo (standard edition) for Windows.
2. Open PowerShell in this folder.
3. Run:

   ```powershell
   hugo server
   ```

4. Open the local address shown by Hugo (normally http://localhost:1313/).

## Publish with GitHub Pages

1. Create a new **public** GitHub repository named `siperliburak.github.io` under your account.
2. In this folder, run:

   ```powershell
   git init
   git add .
   git commit -m "Initial academic website"
   git branch -M main
   git remote add origin https://github.com/siperliburak/siperliburak.github.io.git
   git push -u origin main
   ```

3. In the repository, open **Settings → Pages** and set the source to **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` will build and deploy the site after a push.
5. The initial address will be `https://siperliburak.github.io/`. A custom domain can be connected later.

## Update content

Edit the Markdown files in `content/`. Hugo rebuilds the site when you save changes while `hugo server` is running.

## Before publishing

- Review the biography and every date/title for accuracy.
- Decide whether to publish a downloadable PDF CV; the current CV page is a web summary and does not expose the uploaded PDF.
- Check whether thesis details, preliminary results, and research materials are cleared for public release.
- Confirm that the email address and external profile links should be public.
- Add a profile photograph only if you want one.

## Domain

The project is configured for the free GitHub Pages address initially. A custom domain can be selected later without changing the content structure.
