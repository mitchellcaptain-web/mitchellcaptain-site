# Project Log

A summarised record of the main actions performed on the Mitchell Captain site.

## Site & Repository
- Repository: `mitchellcaptain-web/mitchellcaptain-site`
- Hosting: GitHub Pages (source: `main` branch, root path)
- Live site: https://mitchellcaptain.com.au (also `www.mitchellcaptain.com.au`)

## Actions to Date

### Content
- Created the initial Mitchell Captain marketing page (`index.html`).
- Updated hero and "how it works" legend copy (PR #1):
  - Hero headline → "Unlock the value of the Salesforce platform, in days, not months."
  - Legend → "A senior, local, Salesforce expert" and "Amplified by AI tooling."

### Custom Domain & HTTPS
- Configured custom domain `mitchellcaptain.com.au` via `CNAME`.
- DNS (Cloudflare, DNS-only): apex `A` records → GitHub Pages IPs
  (`185.199.108–111.153`); `www` `CNAME` → `mitchellcaptain-web.github.io`.
- Resolved a stuck TLS certificate by removing and re-adding the custom domain,
  forcing GitHub Pages to re-issue the Let's Encrypt certificate.
- HTTPS certificate issued and approved for apex + `www`; "Enforce HTTPS" enabled.

### Workflow
- Established a branch → commit → push → pull request flow for changes,
  with GitHub Pages auto-deploying from `main` after each merge.
