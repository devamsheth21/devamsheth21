# Devam Sheth - Portfolio Website

A minimal single-page portfolio built with pure HTML & CSS.

## Preview Locally

Run this command in the project folder:

```bash
npx serve .
```

Or if you have Python installed:

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

---

## Editing the Site

### 1. About Section
Edit the content in `index.html` under `<!-- About section -->`. Look for:
- Your bio introduction (the `about-intro` paragraph)
- The timeline entries

### 2. Projects Section
Edit `index.html` under `<!-- Projects section -->`. Each project card has:
- `<h3>` - Project title
- `<p>` - One-sentence description
- `<a>` - GitHub link

### 3. Writing Section
Automatically loads from Medium RSS feed. To change, edit the JavaScript in `index.html`.

### 4. Resume Section
Edit `index.html` under `<!-- Resume section -->`. Update the PDF URL in the button `href`.

### 5. Contact Section
Update social links in the hero section or edit `index.html` under `<!-- Contact section -->`.

---

## Deploying to GitHub Pages

The site is automatically deployed from the `main` branch.

Your site is live at: **https://devamsheth21.github.io**

---

## Customization

### Colors
Edit `style.css` to change colors:
- Primary accent: `#2563eb` (search for this)
- Background: `#fafafa`
- Text: `#333`

---

## License

MIT
