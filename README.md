# Personal Website — Mohammad Farouq Hussain Alomari

A simple personal website with your contact details and bio,
ready to host on GitHub Pages.

## How to publish it (free, public link)

1. **Create a new repository on GitHub:**

   - Go to <https://github.com/new>
   - Name it: `mohammad-farouq-website` (or any name you like)
   - Set it to **Public**
   - Do NOT add a README (you will add your own)

2. **Push the code locally:**

   ```bash
   cd "path\to\mohammad-farouq-website"
   git init
   git add .
   git commit -m "Initial commit: personal website"
   git remote add origin https://github.com/YOUR_USERNAME/mohammad-farouq-website.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**

   - Go to your repository → **Settings** → **Pages**
   - Under **Source**, select **main** and branch **`/`** (root)
   - Click **Save**
   - Your site will be live at:
     `https://YOUR_USERNAME.github.io/mohammad-farouq-website`

4. **Optional — use a custom domain** (e.g., `mohammadalomari.com`)
   in the Pages settings.

## What the site shows

- Name: Mohammad Farouq Hussain Alomari
- Phone: +960 79 745 5154
- Bio: Data Science student at JUST (4th year), from Kafr Kayfiya,
  Irbid, Jordan

## Files

- `index.html` — the website
- `.github/workflows/deploy.yml` — optional auto-deploy to GitHub Pages
