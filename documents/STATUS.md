# Deployment status

- Prepared: November 14, 2026.
- Implementation: complete static HTML/CSS portfolio with local assets and setup documentation.
- GitHub account confirmed: `leahlizrp`.
- GitHub repository: https://github.com/leahlizrp/leah-portfolio
- GitHub Pages: enabled from `main` and `/(root)`.
- Initial build and publication: successful; the public page has been opened and its contents verified.
- Follow-up: portrait sizing fix published and visually verified on the live desktop site.
- Deployment run: https://github.com/leahlizrp/leah-portfolio/actions/runs/43654522784
- Website destination: https://leahlizrp.github.io/leah-portfolio/

## Validation

Local checks passed for all internal anchors, referenced files, five career roles, three selected-work examples, and an exact match between the downloadable resume and the approved PDF. Local HTTP preview was unavailable because the execution environment restricts local sockets. Live browser inspection found a fixed HTML image height causing portrait cropping; CSS now uses height:auto and object-fit:contain, with flexible grid columns. The stylesheet URL is versioned to refresh cached styles.

Live desktop verification passed: the portrait renders at approximately 437.5 × 515.9 pixels, preserving its original proportions; no images are broken and the page has no horizontal overflow. Experience navigation and expanding the Process Color role were tested. The resume download succeeded. UTF-8 punctuation and symbols were verified after a follow-up encoding correction.

Responsive CSS is included, but a requested browser viewport override did not change the actual viewport, so a separate mobile visual check could not be completed in this session.

## Setup performed

Created the public repository under `leahlizrp`, committed the HTML/CSS and supporting files to `main`, uploaded the portrait and approved PDF into `assets`, added setup and maintenance documents under `documents`, and selected `main` / `/(root)` in Settings → Pages. The site uses GitHub's default HTTPS domain.
