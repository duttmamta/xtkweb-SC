# Xtreck Group Static Website

This is a static HTML website for **Xtreck Group**, with two offerings:

- **Xtreck Carbon** — carbon accounting platform
- **Xtreck Support** — complete ownership model of business support

## Included pages

- `index.html` — homepage
- `about.html` — group overview
- `xtreck-carbon.html` — Xtreck Carbon page
- `xtreck-support.html` — Xtreck Support page
- `contact.html` — contact page with demo form
- `privacy.html` — starter privacy page
- `terms.html` — starter terms page

## Structure

```text
xtreck-website/
├── index.html
├── about.html
├── xtreck-carbon.html
├── xtreck-support.html
├── contact.html
├── privacy.html
├── terms.html
├── README.md
└── assets/
    ├── css/
    │   └── style.css
    └── js/
        └── main.js
```

## Local preview

You can open `index.html` directly in a browser, or run a local static server.

### Python

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`

## Deploy options

### GitHub Pages
1. Push these files to a GitHub repository.
2. In repository settings, enable GitHub Pages.
3. Set the source to the root of the main branch.

### Traditional hosting / server
Upload the contents of this folder to the web root for `xtreck.com`.

## Recommended next steps

- Replace placeholder email addresses with your real contact details
- Add your logo and favicon
- Connect the contact form to Formspree, Netlify Forms or your backend
- Add SEO tags, sitemap.xml and robots.txt
- Add analytics and cookie consent if required
- Replace starter legal text with reviewed legal copy
