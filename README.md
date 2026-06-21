# Mitchell Captain

Marketing site for **Mitchell Captain** - AI-native Salesforce delivery and
peace-of-mind managed service. A simple static site (hand-written HTML/CSS, no
build step) served via GitHub Pages on the custom domain
[mitchellcaptain.com.au](https://mitchellcaptain.com.au).

## Files

| File          | Purpose                                              |
| ------------- | ---------------------------------------------------- |
| `index.html`  | The single page (hero, approach, subscriptions, etc) |
| `styles.css`  | Lightweight CSS styled to mimic the SLDS look        |
| `favicon.svg` | Site icon                                            |
| `CNAME`       | Custom domain for GitHub Pages                       |
| `.nojekyll`   | Tells Pages to serve files as-is (no Jekyll build)   |

## Editing

Edit `index.html` / `styles.css` and open `index.html` in a browser to preview.
Commit and push to `main` and GitHub Pages redeploys automatically.

```bash
git add -A
git commit -m "Update site content"
git push
```

## Hosting

- **Host:** GitHub Pages, served from the `main` branch root.
- **Domain:** `mitchellcaptain.com.au` (set via the `CNAME` file + DNS records at
  the domain registrar). HTTPS is provided by GitHub.
