# Akash | AI/ML Developer portfolio

A static, single-page portfolio. No build step and no dependencies: `index.html` is the whole site.

## Deploy to Vercel

**Option 1: drag and drop (fastest)**
1. Go to https://vercel.com/new and sign in.
2. Drag this whole folder onto the page (or choose "Deploy" with the folder zipped and unzipped first).
3. Leave the framework preset as **Other**. No build command and no output directory are needed.
4. Click **Deploy**. Your site is live at `https://<project-name>.vercel.app`.

**Option 2: GitHub (updates on every push)**
1. Create a new GitHub repository and upload these files to its root.
2. On https://vercel.com/new choose **Import Git Repository** and pick it.
3. Framework preset **Other**, then **Deploy**.

**Option 3: Vercel CLI**
```bash
npm i -g vercel
cd akash-portfolio
vercel --prod
```

## Custom domain
Project → **Settings → Domains** → add your domain and follow the DNS instructions.

## Files
- `index.html` the portfolio (HTML, CSS and JavaScript in one file)
- `vercel.json` clean URLs and basic security headers
- `404.html` custom not-found page
- `robots.txt` allows search engines

## Editing
- Email and LinkedIn: search `index.html` for `makash20067@gmail.com` and `linkedin.com/in/akash-m-533a43345`.
- Certificates: edit the list named `C` in the script.
- Fonts load from Google Fonts, so the page needs internet access to show Fraunces and Manrope. It falls back to Georgia and system fonts otherwise.

## Notes
- The "Open in Gmail" buttons open Gmail's compose window in a new tab. The "mail app" link uses `mailto:` for other email apps.
- Keyboard shortcuts: **J** / **K** for next and previous page, **L** for the desk lamp.
