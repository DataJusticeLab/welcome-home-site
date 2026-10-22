# Welcome Home public site

Tiny static marketing site and privacy policy for the Welcome Home app. Plain HTML and CSS, no build step.

- `index.html` - logo, description, footer
- `privacy.html` - privacy policy (required by Google Play and the App Store)
- `style.css`, `assets/logo.png`

## Hosting

This should live in its own **public** GitHub repository. The app repo is private on a free plan, so GitHub Pages cannot serve from it.

1. Push this folder to a new public repo.
2. Repo Settings -> Pages -> Build and deployment -> Deploy from a branch -> branch `main`, folder `/ (root)`.
3. The site appears at `https://<owner>.github.io/<repo>/`. All links are relative, so it works there and from `file://`.

## Custom domain (not set up yet)

No `CNAME` file is committed because the domain and owner are undecided. To add one:

1. Add a file named `CNAME` at the repo root containing only the domain, e.g. `www.mywelcomehome.org`.
2. At the DNS provider, add a `www` CNAME record pointing to `<owner>.github.io`, or for an apex domain add A records to `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` (and AAAA records if desired, per GitHub's docs).
3. In Settings -> Pages, confirm the domain and enable "Enforce HTTPS".

## Before going live

Fill in every `[...]` placeholder in `index.html` and `privacy.html` (organization name, legal name, contact email, effective date, mailing address). Have the privacy policy reviewed, and update it whenever the app's data practices change.
