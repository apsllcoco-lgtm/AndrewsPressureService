# Andrew’s Pressure Services — Editable Website

## What is included
- Static website (`index.html`)
- Photo gallery data (`content/gallery.json`)
- Business settings (`content/settings.json`)
- Pages CMS configuration (`.pages.yml`)
- Photo upload directory (`media/`)

## Enable your free editing dashboard
1. Create a free GitHub account and repository, and upload **all** files and folders from this package, including the hidden `.pages.yml` file. Keep the repository private if desired, subject to your hosting/CMS setup.
2. Go to https://pagescms.org and sign in with GitHub; authorize access to the website repository.
3. Choose your repository. The editor uses `.pages.yml` to show **Website Settings** and **Before and After Gallery**.
4. Open the gallery, add a project with a title, city, service, before photo, after photo and optional description; save the changes.
5. Publish the GitHub repository through Cloudflare Pages (free tier). Configure production branch and static root directory; no build command required. After new edits are committed, your host will redeploy automatically if Git integration is enabled.

## Important
- A local `file://` preview will not load JSON data due to browser security. Preview with a local HTTP server, for example `python -m http.server 8000`, then visit `http://localhost:8000`.
- Square is **not yet connected**. Add only your verified Square payment URL in Website Settings. Payments take place on Square's secure website.
- The quote form currently opens the visitor's email app and requires a business email to be set. It does not submit to a database. A form service can be added later.
- Pages CMS and hosting free tiers, permissions, and setup may change; check provider terms.
- Do not add photos without permission or post identifying customer information without consent.
