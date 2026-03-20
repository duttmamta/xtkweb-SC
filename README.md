# Xtreck Group Website

Static HTML website for Xtreck Group, including:
- Home page
- About page
- Xtreck Carbon page
- Xtreck Support page
- Contact page
- Privacy Policy
- Terms & Conditions

## Structure

- `index.html`
- `about.html`
- `xtreck-carbon.html`
- `xtreck-support.html`
- `contact.html`
- `privacy.html`
- `terms.html`
- `assets/css/style.css`
- `assets/js/main.js`

## Local preview

Open `index.html` in a browser, or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy to GitHub

```bash
git init
git add .
git commit -m "Initial Xtreck Group website"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main
```

## Notes

- The contact form is currently static.
- Replace legal placeholder text before launch.
- You can deploy this as a static site on GitHub Pages, Netlify, Vercel, S3/CloudFront, or your own hosting.
