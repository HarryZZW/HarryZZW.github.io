# Zhengwei (Harrison) Zhang academic website

This is a static, GitHub Pages-ready academic website for the job market.

## What's included

- `index.html` - one-page academic website
- `styles.css` - local stylesheet, no external dependencies
- `assets/docs/CV_Zhengwei_Zhang_public.pdf` - public CV with phone number removed
- `assets/docs/Job_Market_Paper_Zhengwei_Harrison_Zhang.pdf` - job market paper
- `assets/docs/Research_Statement_Zhengwei_Zhang.pdf` - research statement
- `404.html` - basic error page
- `.nojekyll` - tells GitHub Pages to serve files as-is
- `.gitignore` - helps avoid committing local secrets and temporary files

## Recommended GitHub Pages setup

1. Create a repository named `USERNAME.github.io`, replacing `USERNAME` with your GitHub username.
2. Upload the files in this folder to the root of the repository.
3. In the repository, go to **Settings > Pages**.
4. Set the source to deploy from the `main` branch and the root folder `/`.
5. Visit `https://USERNAME.github.io` after GitHub finishes publishing.

## Security-minded setup notes

- Keep this site static: no contact forms, no databases, no server-side code, and no external JavaScript.
- Use a strong unique GitHub password plus 2FA or passkeys.
- Store recovery codes safely in a password manager.
- Do not commit secrets, private data, API keys, raw datasets, unpublished confidential material, or SSH keys.
- Avoid adding random GitHub Actions or third-party scripts. This package does not need GitHub Actions.
- Use branch protection or repository rules for `main` after the site is published.
- If you use a custom domain, verify the domain in GitHub before connecting it, and enforce HTTPS.
- Review the PDF files before publishing. The included CV removes the phone number from the first page, but the site still publishes your academic email and institution.

## Updating content

Edit `index.html` directly. The site is intentionally simple so that you can review every line that gets published.
