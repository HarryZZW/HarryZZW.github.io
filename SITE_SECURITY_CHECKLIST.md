# Website Safety Checklist

Before publishing or updating the GitHub repository:

- Confirm the repository contains only files you are comfortable making public.
- Confirm `index.html` is at the repository root, not inside an extra folder.
- Confirm the only PDF in `assets/docs/` is `CV_Zhengwei_Zhang_public.pdf`.
- Delete any old job market paper or research statement PDFs from the repository.
- Replace `assets/img/profile.jpg` with your real headshot if you want the live site to show your photo.
- Keep GitHub two-factor authentication enabled.
- Do not add API keys, passwords, private data, `.env` files, or unpublished datasets.
- Keep the site static unless you have a specific reason to add external services.

If the previous job market paper or research statement PDFs were already committed to a public GitHub repository, deleting them from the current version removes them from the live file tree, but not necessarily from Git history or external caches. For a simple personal website, the cleanest option is often to create a fresh repository and upload only this revised package.
