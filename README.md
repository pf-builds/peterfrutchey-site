# peterfrutchey.com

Static consulting site for Peter Frutchey. One `index.html`, no build step. Hosted on GitHub Pages, custom domain peterfrutchey.com.

## Setup, already done
1. **Formspree ID** — wired up in the contact form's `action` attribute.
2. **Headshot** — `headshot.jpg` in the hero, 800x1000 (4:5), all EXIF stripped.

## Replacing the headshot
The hero slot is 4:5. Export at **800x1000**, JPG quality ~86, under ~200KB, named `headshot.jpg`.
**Strip EXIF before committing** — phone photos embed GPS coordinates, and anything in this repo is publicly downloadable.

## Editing
Change `index.html`, commit, push. GitHub Pages redeploys in about a minute.

## Notes
- `CNAME` holds the custom domain. Do not delete it.
- Content claims are capped to what's true and public. Do not add invented metrics or testimonials.
