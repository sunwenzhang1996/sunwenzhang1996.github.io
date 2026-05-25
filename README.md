# Wenzhang Sun Homepage

This is a lightweight al-folio-style academic homepage tailored for GitHub Pages.

It is intentionally static: no Ruby, Jekyll, npm, or local server is required for deployment. GitHub Pages can serve the files directly from the repository root.

## Deploy on GitHub Pages

1. Create a GitHub repository named `YOUR_USERNAME.github.io`.
2. Copy all files from this folder into that repository.
3. Push to GitHub.
4. In GitHub, open `Settings -> Pages`.
5. Select `Deploy from a branch`, choose `main` and `/root`.
6. Wait for GitHub Pages to publish the site.

## Local preview

You can open `index.html` directly in a browser.

For a cleaner local preview:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- The official al-folio repository was slow to download in this environment, so this folder uses an al-folio-inspired static structure.
- Update under-review paper statuses before making the site public.
- Add real project thumbnails under `assets/img/` if desired.
