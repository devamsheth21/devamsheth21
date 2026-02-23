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
- The bullet points list (`about-list`)

### 2. Projects Section
Edit `index.html` under `<!-- Projects section -->`. Each project card has:
- `<h3>` - Project title
- `<p>` - One-sentence description
- `<a>` - GitHub link

Replace the placeholder URLs with your actual GitHub repos.

### 3. Writing Section
Edit `index.html` under `<!-- Writing section -->`. Update:
- Individual post titles and URLs in the `writing-list`
- "View all posts on Medium" link
- "View all posts on Substack" link

### 4. Resume Section
Edit `index.html` under `<!-- Resume section -->`. Update the PDF URL in the button `href`.

### 5. Contact Section
Edit `index.html` under `<!-- Contact section -->`. Update:
- Email address
- GitHub profile URL
- LinkedIn profile URL

---

## Deploying to GitHub Pages

1. Push these files to your repository:
   ```bash
   git add index.html style.css README.md
   git commit -m "Add portfolio website"
   git push origin main
   ```

2. Go to https://github.com/devamsheth21/devamsheth21/settings/pages

3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** 
   - Folder: **/(root)**

4. Click Save and wait 1-2 minutes.

5. Your site will be live at: **https://devamsheth21.github.io**

---

## Customization

### Colors
Edit `style.css` to change colors:
- Primary accent: `#2563eb` (search for this)
- Background: `#fafafa`
- Text: `#333`

### Typography
The site uses system fonts by default (fastest, no external dependencies).

---

## License

MIT
