# Thinkroid Website

Marketing website for [Thinkroid](https://www.thinkroid.com/) — building intelligent tools for the future of work.

## Structure

```
Thinkroid-Website/
├── index.html              # Homepage
├── about/index.html        # About page
├── blog/index.html         # Blog
├── contact/index.html      # Contact form
├── contact/thank-you/      # Form confirmation
├── 404.html                # Error page
├── css/shared.css          # Design system
├── assets/                 # Logo, favicons, OG image
├── CNAME                   # Custom domain: www.thinkroid.com
├── sitemap.xml
├── robots.txt
└── site.webmanifest
```

## Development

Static HTML site — no build step required. Open `index.html` in a browser or use any local server:

```bash
npx serve .
```

## Deployment

Deployed via GitHub Pages with custom domain `www.thinkroid.com`.

## License

[CC BY-SA 4.0](LICENSE)
