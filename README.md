# Orooj Financial Group — website

Static single-page site (all styles, scripts and images are inlined in `index.html`).

## Deploy to Hostinger

**Option A — Git deploy (hPanel → Websites → Advanced → Git)**
1. Repository: `https://github.com/Mesumraza08-art/ourooj-financials-.git`, branch `main`.
2. Install path: leave empty (deploys to `public_html`).
3. Click **Deploy**. Enable auto-deployment via the webhook if you want pushes to go live automatically.

**Option B — File Manager / FTP**
Upload `index.html`, `.htaccess` and `robots.txt` into `public_html`.

The `.htaccess` forces HTTPS, enables gzip and sets caching/security headers.
