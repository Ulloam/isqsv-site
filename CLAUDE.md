# isqsv-site

Static website for isqsv.com, hosted via GitHub Pages.

## Stack
- Plain HTML/CSS/JS (no frameworks)
- GitHub Pages for hosting
- GoDaddy DNS pointing to GitHub Pages IPs
- Domain: isqsv.com (registered at GoDaddy, active through 2028)

## Structure
- `index.html` — landing page
- `styles.css` — site styles
- `CNAME` — GitHub Pages custom domain config

## Deployment
Push to `main` branch → GitHub Pages auto-deploys.

## DNS (GoDaddy)
A records point to GitHub Pages IPs (185.199.108-111.153).
CNAME `www` → `Ulloam.github.io`.
MX and email-related CNAMEs preserved for M365 email (mani@isqsv.com, Lyndsey@isqsv.com).
