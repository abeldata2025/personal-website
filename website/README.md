# Abel Wabella Sugebo — Personal Website

Professional portfolio site for Abel Wabella Sugebo, media integrity researcher, AI governance expert, and founder of Inform Africa / HaqCheck.

## Live Site

🔗 [View Website](https://abelsugebo.netlify.app) *(update this URL after deployment)*

## About

Single-page professional website featuring:
- Professional bio and expertise overview
- Resume / career timeline
- Selected research and publications
- Media mentions and press coverage
- Partnership and collaboration opportunities
- Contact form

## Tech Stack

- Pure HTML/CSS/JavaScript (no frameworks, no build tools)
- Google Fonts (DM Serif Display, Source Sans 3, JetBrains Mono)
- Hosted on Netlify (free tier)

## Updating Content

Open `index.html` in any text editor. Search for the section you want to update:

| Section | Search for | What to do |
|---------|-----------|------------|
| Work items | `work-grid` | Copy a `work-card` div, edit title/description |
| Media mentions | `media-grid` | Copy a `media-item` div, edit source/title |
| Resume | `timeline` | Copy a `timeline-item` div, edit role/org |
| Contact info | `contact-methods` | Edit email or location text |

After editing, push to GitHub — Netlify auto-deploys.

### Updating the CV

The "Download Full CV (PDF)" button serves `Abel-Sugebo-CV.pdf` from this folder. To update it, upload a new PDF with exactly that file name (replacing the old one). No HTML change is needed.

### Contact form

The form posts to Formspree (form ID `mpqyyvno`), which emails each message to Abel. Submissions, spam filtering and the monthly limit are managed in the Formspree dashboard. If the form ID ever changes, update the `action` URL on the `<form id="contactForm">` tag in `index.html`.

## License

© 2026 Abel Wabella Sugebo. All rights reserved.
