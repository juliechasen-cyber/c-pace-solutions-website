# C-PACE Solutions website

Live site: https://c-pacesolutions.com (hosted on Netlify, site name `c-pace-solutions`).

Plain HTML, no build step. The files in this folder are the site.

- `index.html` — home page (includes the contact form and the calculator)
- `services.html` — services page
- `thank-you.html` — shown after the contact form is sent
- `images/` — all photos and logos (`images/deals/` holds the deal photos and logos)

## Making a change

1. Edit the HTML file (or swap an image in `images/`, keeping the same file name).
2. Commit and push to `main`.
3. Deploy to Netlify (see below).

## Deploying

The live site was first uploaded by drag-and-drop (2026-11-11). Until this repo is linked to the Netlify
site, push to GitHub only saves the change; it does not publish it. To publish, either link the repo in
Netlify (Project configuration > Build & deploy > Link repository, then push = deploy) or drag this folder
onto the Netlify deploy page. Each Netlify deploy uses credits from a shared pool, so batch changes.

## Contact form

The form is `name="contact"` with `data-netlify="true"` (Netlify Forms) and posts to `/thank-you`.
Keep the name and attribute when editing. Notifications are set up in Netlify under Forms.
