# How this portfolio was set up

Prepared November 14, 2026.

## 1. Content and design

The site was built from Leah's approved two-page navy resume and the fuller role descriptions she approved in conversation. The opening career story is preserved, including the previously requested removal of three repeated profile sentences. Experience details are grouped under expandable role headings, so the website can retain the full detail without the two-page resume limit.

The supplied portrait is displayed with rounded corners using CSS; the image file itself is unchanged. The palette follows the resume: navy, warm off-white and muted blue, with a restrained warm accent.

## 2. Implementation

Created `index.html`, `styles.css` and `assets/`. No framework, package install, database, API key or build process is required. Native HTML `details` and `summary` elements provide keyboard-accessible expandable content. Relative asset URLs work both locally and under a GitHub Pages project path.

The page includes a skip link, labelled navigation, image alternative text, keyboard focus styles, responsive layouts and reduced-motion support. The download buttons point to the supplied two-page PDF. Email and phone links use `mailto:` and `tel:`; there is no contact-form backend.

## 3. Publish with GitHub Pages

These steps are for a dedicated repository named `leah-portfolio` in the connected `leahlizrp` GitHub account. Use a different name only if desired; a project site's URL follows its repository name.

1. Sign in to GitHub and create a new public repository named `leah-portfolio`. Leave the initial README, license and .gitignore options unchecked when uploading this prepared project.
2. Upload the contents of this folder to the repository root, including `index.html`, `styles.css`, `assets/`, `documents/`, `README.md` and `.nojekyll`. Do not upload only the ZIP, and do not put the project inside an extra wrapper folder.
3. Commit the files to the `main` branch.
4. Open repository **Settings  Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose **main**, then **/(root)**, and save.
7. Wait for the Pages deployment to succeed. Use the URL shown by GitHub in Pages settings; the expected project URL is `https://leahlizrp.github.io/leah-portfolio/`.
8. Open the published page, expand a career role, follow a navigation link and test the PDF download. Check it on a phone as well.

GitHub Pages serves a public website, including the published photo, contact information and downloadable resume. Only the portfolio project folder should be uploaded; no employer records or other workspace files are needed.

## 4. Future updates

Edit the files, preview locally, then commit changes to `main`. Branch-based GitHub Pages publishing will redeploy those changes. Read `EDITING.md` before changing credential statuses or time-sensitive text.

## Official references

Checked November 14, 2026:

- [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Configuring a publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

For a future framework migration, keep this version as the working baseline and configure the framework's static output for GitHub Pages. No framework migration is required for this version.

