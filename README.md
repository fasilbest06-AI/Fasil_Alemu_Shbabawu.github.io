# Fasil Alemu Shbabawu — Academic & Professional Portfolio

Responsive static portfolio for GitHub Pages. Built with HTML, CSS, and vanilla JavaScript.

## Project structure

```text
.
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   ├── images/
│   └── documents/
│       └── resume.pdf
└── README.md
```

## Personalize before publishing

1. In `index.html`, replace `YOUR_EMAIL@example.com` with your public contact email.
2. Replace the LinkedIn, ORCID, and Google Scholar placeholder links with your real profile URLs.
3. Add your CV PDF at `assets/documents/resume.pdf`. If you use a different filename, update the CV link in `index.html`.
4. Add a profile photo to `assets/images/` if desired; the current design uses an abstract CSS illustration and does not require a photo.
5. Verify the PhD institution/program details, dates, degree years, publication status, and project descriptions before publishing.
6. Replace example project links with the actual public repository links.

## Publish using GitHub Pages

1. Open `https://github.com/fasilbest06-AI/Fasil_Alemu_Shbabawu.github.io`.
2. Upload the contents of this folder to the repository root. Upload the folders `css`, `js`, and `assets` as folders; do not upload the enclosing ZIP or parent folder as the site root.
3. Commit the files to the `main` branch.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Choose branch `main` and folder `/(root)`, then save.
7. Wait for deployment and open the URL displayed in the Pages settings.

Expected URL:
`https://fasilbest06-ai.github.io/Fasil_Alemu_Shbabawu.github.io/`

## Local preview

Open `index.html` in a browser. No package installation or build command is required.

## Notes

- This is a static website. It has no server-side contact form, database, login, or private admin area.
- The theme preference is stored in the visitor's browser using localStorage.
- Google Fonts are loaded from Google Fonts; system fallback fonts are provided.
