# Fulcria Labs Website

Company website for [fulcria.com](https://fulcria.com) - landing page + blog.

## Structure

```
fulcria-landing/
├── index.html          # Landing page (static HTML)
├── _config.yml         # Jekyll configuration
├── CNAME               # GitHub Pages custom domain
├── robots.txt          # Search engine directives
├── sitemap.xml         # Sitemap for SEO
├── _posts/             # Blog posts (Jekyll markdown)
├── _includes/          # Jekyll includes
├── blog/
│   └── index.md        # Blog listing page
└── assets/             # Images, CSS, etc.
```

## URLs

- **Landing**: https://fulcria.com
- **Blog**: https://fulcria.com/blog/
- **Posts**: https://fulcria.com/blog/post-slug/

## Deployment

GitHub Pages with Jekyll. Push to main branch to deploy.

## Local Development

```bash
# Install Jekyll
gem install bundler jekyll

# Run locally
bundle exec jekyll serve

# View at http://localhost:4000
```

For just the landing page, open `index.html` in a browser.

## Links

- **Swing Analyzer**: https://swing.fulcria.com
- **Blog**: https://fulcria.com/blog
- **GitHub**: https://github.com/Fulcria-Labs
