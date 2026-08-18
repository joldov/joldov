# jessicaoldov.dev

Personal portfolio site. Plain HTML/CSS/JS, no build step.

## Files
- `index.html` — page content
- `style.css` — all styling (colors, type, layout live in `:root` at the top)
- `script.js` — highlights the current section in the nav as you scroll
- `Jessica_Oldov_Resume.pdf` — add your resume PDF here with this filename (or update the link in `index.html`)

## Deploy on GitHub Pages
1. Create a new repo, e.g. `github.com/<your-username>/<your-username>.github.io` (this exact naming gives you a URL with no `/repo-name` suffix — otherwise any repo name works, just with `/repo-name` in the URL).
2. Push these files to the repo root:
   ```
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**, set **Source** to `Deploy from a branch`, branch `main`, folder `/root`, then save.
4. Your site will be live at `https://<your-username>.github.io/` (or `/<repo-name>/`) in a minute or two.

## Before you push
- Swap the placeholder `href="https://github.com/"` and `https://linkedin.com/"` links in `index.html` and the footer for your real profile URLs.
- Drop your resume PDF into this folder as `Jessica_Oldov_Resume.pdf`, or change the link target.
- If you buy `joldov.com`, add a `CNAME` file containing just the domain, then point your DNS at GitHub Pages.

## Customizing
Every color, font, and spacing token lives at the top of `style.css` under `:root` — change the gradient stops, ink color, or fonts there and it cascades everywhere.
