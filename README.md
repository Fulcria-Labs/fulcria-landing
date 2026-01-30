# Fulcria Labs Landing Page

Company landing page for [fulcria.com](https://fulcria.com).

## Structure

- `index.html` - Main landing page
- `robots.txt` - Search engine directives
- `sitemap.xml` - Sitemap for SEO
- `CNAME` - Custom domain for GitHub Pages

## Deployment

This site is designed to be deployed to GitHub Pages with a custom domain.

### Setup Steps

1. Create GitHub repo `Fulcria-Labs/fulcria-landing`
2. Push this code to the repo
3. Enable GitHub Pages (Settings > Pages > Source: main branch)
4. Configure Cloudflare DNS to point to GitHub Pages:
   - A record: `fulcria.com` → `185.199.108.153`
   - A record: `fulcria.com` → `185.199.109.153`
   - A record: `fulcria.com` → `185.199.110.153`
   - A record: `fulcria.com` → `185.199.111.153`
   - CNAME: `www.fulcria.com` → `fulcria-labs.github.io`
5. Wait for DNS propagation and SSL certificate

## Local Development

Just open `index.html` in a browser. No build step required.

## Links

- **Swing Analyzer**: https://swing.fulcria.com
- **Blog**: https://fulcria-labs.github.io
- **GitHub**: https://github.com/Fulcria-Labs
