# Editing the portfolio

## Text and career history

Open `index.html` in a text editor. Major sections have the IDs `story`, `work`, `experience`, `skills`, `education` and `contact`. Change the visible words between HTML tags while keeping the surrounding tags intact.

The selected-work examples are narrative descriptions based on the approved resume. They do not link to private employer files, and they do not claim measured outcomes that were not supplied.

Each career role is a `details` element with a `summary` heading. Add `open` to a particular `details` opening tag if that role should be expanded on first load. The page does not require JavaScript.

## Photo and resume

- Replace `assets/leah-reynolds.png` to update the portrait. If its aspect ratio changes, update the HTML width/height and CSS aspect ratio together.
- Replace `assets/Leah-Reynolds-Resume.pdf` to update the download. Keep the same filename to preserve the links.
- Photo corner rounding is controlled by `.portrait img` in `styles.css`.

## Colours and spacing

The `:root` block at the top of `styles.css` contains the navy, cream, accent and text colours. The `.wrap` selector sets maximum content width and side padding. Media queries near the bottom handle narrower screens.

## Time-sensitive details

As of November 14, 2026:

- AASP QHSO and Internal Auditor training are in progress, nearing completion. Do not mark them earned until completed.
- The profile retains the approved expectation of completion within four months. Update this sentence when status changes.
- Standard First Aid with CPR recertification is scheduled for December 12-13, 2026, not presented as already completed.
- Previous forklift certification requires recertification.
- Review the current role dates, contact information, footer year and credential-status update date when making changes.

## Quick checks after editing

Open the page at desktop and phone widths. Check navigation targets, expandable roles, focus visibility and the PDF link. Confirm images load and no text runs off screen. Then commit the changes to GitHub.

