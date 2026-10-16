# Bamidele Idris Oluwakayode — Portfolio

Responsive static portfolio for public health, medical demography, field research, and developing data-analysis work. Built with HTML, CSS, and vanilla JavaScript; designed for free GitHub Pages hosting.

## Files
- `index.html` — page content
- `styles.css` — responsive layout and visual styles
- `script.js` — mobile navigation and current year
- `assets/` — replaceable SVG placeholders and favicon

## Personalise your images
1. Upload your professional photo into `assets/`, for example `profile.jpg`.
2. In `index.html`, replace `assets/profile-placeholder.svg` with `assets/profile.jpg`.
3. Replace gallery image references with your own images, e.g. `assets/fieldwork.jpg`, `assets/research.png`, and `assets/training.jpg`.
4. Keep image file names simple and match the names used in the HTML. JPG, PNG, and WebP are supported by browsers.
5. Only share field photographs when authorised. Do not publish identifiable research participants, confidential documents, or personal data without appropriate consent.

## Add certificates (simple GitHub method)

The portfolio includes a **Certificates & Training** section with starter cards. The links are not active until you add the matching certificate files and update each card.

1. Place a clear PDF scan of each certificate in `assets/certificates/`. Suggested filenames are `hts-training.pdf` and `no-means-no.pdf`. Use the exact file names you reference in the HTML.
2. In `index.html`, find the relevant certificate card and replace its `certificate-pending` status with links such as:

```html
<a class="certificate-link" href="assets/certificates/hts-training.pdf" target="_blank" rel="noreferrer">View certificate ↗</a>
<a class="certificate-link" href="assets/certificates/hts-training.pdf" download>Download PDF ↓</a>
```

3. Verify the exact title, issuing organisation, and date against the document. Copy an existing `<article class="certificate-card">...</article>` block to add more cards.
4. Upload/commit the updated files to the `main` branch of your `bamidehouse1.github.io` repository. GitHub Pages will publish the changes automatically.

**Privacy tip:** publish only certificates you are comfortable sharing publicly. Before uploading, consider hiding certificate ID numbers, QR codes, signatures, or other details that could be misused, while keeping the issuer, qualification, and date visible where appropriate. Do not upload certificates containing sensitive personal information.

This is the starter approach (Option C): easy-to-maintain files in GitHub now, with the site structure ready to be extended later. A true upload dashboard would require a separate backend or cloud-storage service; GitHub Pages alone cannot securely receive and store uploads.

## Add your CV
Upload your approved CV as `assets/Bamidele_Idris_Oluwakayode_CV.pdf`. In `index.html`, replace the current CV `mailto:` link with:

```html
<a class="button button-light" href="assets/Bamidele_Idris_Oluwakayode_CV.pdf" download>Download CV ↗</a>
```

Review the CV for private information before publishing it publicly.

## Contact links included
- Email: `bamidehouse1@gmail.com`
- GitHub: `https://github.com/bamidehouse1`
- LinkedIn: `https://www.linkedin.com/in/idris-bamidele-35681b253`

Edit these in `index.html` if needed.

## Publish on GitHub Pages
1. Sign in to GitHub as `bamidehouse1`.
2. Create a **public** repository named exactly `bamidehouse1.github.io`.
3. Upload the *contents* of this folder to the repository root. `index.html` must be at the top level, not inside a nested project folder.
4. Commit the files.
5. Open **Settings → Pages**. Select **Deploy from a branch**, choose `main` and `/(root)`, then save.
6. After deployment, the website should be available at `https://bamidehouse1.github.io/`.

The first deployment can take a few minutes. Check the repository's Actions tab and Pages settings if it does not appear.

## Accuracy notes
- The dissertation and R project are presented as work in progress.
- The chart is decorative and is not a result from the analysis.
- Review experience statements and adjust anything that does not precisely reflect your personal contribution.
- Add project repository links only after those projects are actually published.
