# HOT — House of Thunder Website

This is the official website for **House of Thunder**, served at **https://houseofthunder.org**.

## What this is
A single-page static website. There is no database or server code — just an
`index.html` file (the page) plus a few supporting files. It is hosted for free
by **GitHub Pages**, which publishes whatever is in this repository.

## How updates work
1. Edit `index.html` (or the images/fonts) in this folder.
2. Save your changes.
3. "Commit" the changes and "push" them to GitHub (your assistant does this for you).
4. GitHub Pages rebuilds the site automatically — usually within a minute or two.

In short: **every time changes are pushed here, the live website updates.**

## Folder contents
- `index.html` — the website page itself (text, layout, and styles all live here).
- `CNAME` — tells GitHub to use the custom domain `houseofthunder.org`.
- `logo.png` — the HOT logo used in search results and structured data.
- `og-image.png` — the preview image shown when the site is shared on social media.
- `fonts/` — the website's fonts, stored locally so the page does not depend on
  outside services to look right.

## Custom domain
The site uses the domain `houseofthunder.org` (configured via the `CNAME` file
and GitHub Pages settings). DNS is managed at Namecheap and points to GitHub's
servers.

## Notes
- No build step is required — what you see in the repo is what gets published.
- If something looks broken on the live site, check that the latest changes were
  pushed and wait a minute or two for GitHub Pages to finish building.
