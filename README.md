# Pre-Achievement Framework — GitHub Pages Site

Static launch site for **preachievementframework.com**.

## Files

- `index.html` — landing page
- `styles.css` — all page styles; no framework required
- `assets/pre-achievement-framework.svg` — official Figure 3
- `assets/Beyond-the-Achievement-Gap.pdf` — publication-ready report
- `assets/favicon.svg` — site icon
- `assets/social-card.png` — social sharing image
- `CNAME` — custom domain for GitHub Pages
- `.nojekyll` — tells GitHub Pages to serve files directly
- `404.html` — simple not-found page

## Publish on GitHub Pages

1. Create a new public GitHub repository, for example `preachievementframework`.
2. Upload the contents of this folder to the repository root and commit to `main`.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Set the custom domain to `preachievementframework.com`.
6. At your domain registrar, add the DNS records GitHub currently instructs for an apex custom domain.
7. After DNS resolves and GitHub provisions the certificate, enable **Enforce HTTPS**.
8. Verify the custom domain in your GitHub account settings as an additional security step.

Because GitHub's DNS values and UI can change, use the current GitHub Pages documentation when entering DNS records rather than copying old values from a tutorial.

## Before launch

- Preview the site on desktop and mobile.
- Confirm `assets/Beyond-the-Achievement-Gap.pdf` opens correctly.
- Confirm the Figure 3 SVG renders correctly.
- Replace or add public contact/social links only when you decide which accounts should be associated with the framework.

No external fonts, JavaScript frameworks, analytics, trackers, or third-party dependencies are required.

## Custom-domain note

GitHub currently recommends configuring both the apex domain and the `www` subdomain for HTTPS-secured Pages sites. If `preachievementframework.com` is the custom domain in Pages and both DNS variants are configured correctly, GitHub can redirect the `www` variant to the apex domain. Domain verification is also recommended to reduce takeover risk.
