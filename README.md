# Zhengwei (Harrison) Zhang - Job Market Website

This is a static GitHub Pages website package. It is designed to be uploaded directly to the root of your `USERNAME.github.io` repository.

## What is included

- `index.html` - the main website page
- `styles.css` - the UT Austin-inspired visual styling
- `assets/docs/CV_Zhengwei_Zhang_public.pdf` - public CV only
- `assets/img/profile.jpg` - temporary profile-image placeholder
- `404.html`, `.nojekyll`, `.gitignore`, and `robots.txt`

## What is intentionally not included

The job market paper PDF and research statement PDF are not included in this version. The website still summarizes your research, but the manuscript and research statement cannot be downloaded from this package.

Important: if you already uploaded the earlier package to GitHub, you should delete the old PDF files from your GitHub repository too. Removing links from `index.html` is not enough if the files are still present in `assets/docs/`.

Old files to remove from GitHub if they exist:

- `assets/docs/Job_Market_Paper_Zhengwei_Harrison_Zhang.pdf`
- `assets/docs/Research_Statement_Zhengwei_Zhang.pdf`
- `assets/docs/Zhengwei_Harrison_Zhang_Job_Market_Paper.pdf`
- `assets/docs/Zhengwei_Zhang_Research_Statement.pdf`

## How to add your real profile photo

1. Choose a professional headshot, ideally square, such as 800 x 800 pixels or larger.
2. Rename it exactly: `profile.jpg`
3. Replace the placeholder file here: `assets/img/profile.jpg`
4. Re-upload or commit the changed file to GitHub.

The website automatically crops the image to a square profile card, so a normal rectangular headshot will still work.

## How to publish on GitHub Pages

Upload the contents of this folder directly to the root of your `USERNAME.github.io` repository. When you open the repository, `index.html` should be visible immediately at the top level.

Recommended Pages settings:

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/ (root)`

## Safety notes

- This site contains no JavaScript.
- It uses no contact form, database, tracking scripts, analytics scripts, external fonts, or third-party assets.
- The contact email is shown as Harrison.Zhang@mccombs.utexas.edu and linked with a mailto address.
- Do not upload private drafts, datasets, passwords, API keys, `.env` files, or private notes to this repository.
