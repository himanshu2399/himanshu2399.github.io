# Himanshu Soni — Portfolio Website

A minimal, single-file portfolio site (`index.html`). No build step, no dependencies — just one HTML file you can host for free.

---

## 🚀 Deploy free on GitHub Pages (recommended)

GitHub Pages hosts static sites for free at `https://<your-username>.github.io`. You already have a GitHub account (`himanshu2399`), so this takes about 5 minutes.

### Option A — The simplest path (username site, no custom repo name needed)

1. **Create a new repository** named exactly:
   ```
   himanshu2399.github.io
   ```
   Go to https://github.com/new → Repository name: `himanshu2399.github.io` → set to **Public** → click **Create repository**.

2. **Upload `index.html`:**
   - On the new repo page, click **"uploading an existing file"** (or the **Add file → Upload files** button).
   - Drag in `index.html`.
   - Click **Commit changes**.

3. **Wait ~1 minute**, then visit:
   ```
   https://himanshu2399.github.io
   ```
   That's your live site. 🎉 (For a repo named `<username>.github.io`, Pages is enabled automatically.)

### Option B — Any repo name (e.g. `portfolio`)

1. Create a public repo, e.g. `portfolio`, and upload `index.html` (same as above).
2. Go to the repo's **Settings → Pages**.
3. Under **"Build and deployment" → Source**, choose **Deploy from a branch**.
4. Set branch to **`main`** and folder to **`/ (root)`**, then **Save**.
5. After a minute, your site is live at:
   ```
   https://himanshu2399.github.io/portfolio
   ```

> Tip: If you prefer using Git from your terminal instead of the web uploader:
> ```bash
> git init
> git add index.html
> git commit -m "Add portfolio site"
> git branch -M main
> git remote add origin https://github.com/himanshu2399/himanshu2399.github.io.git
> git push -u origin main
> ```

---

## ✏️ How to customize

Everything lives in `index.html`. Open it in any text editor.

- **Add your real GitHub projects:** find the `<!-- WORK / PROJECTS -->` section. Copy one `<article class="project"> ... </article>` block and edit the title, description, and tags. Add a live link by wrapping the title, or add an `<a>` like the one in the "More on GitHub" card.
- **Add an "Open to work" badge:** in the hero, the `status-chip` currently reads *"Senior DevOps Engineer @ Onix."* Change that text to whatever you like (e.g. "Open to DevOps / SRE opportunities").
- **Add your phone number:** it was intentionally left off the public site to reduce spam. To add it, drop another `<a class="btn btn-ghost" href="tel:+91...">` into the Contact section.
- **Change the accent color:** edit `--accent` (and `--accent-ink`, `--accent-soft`) in the `:root` block near the top of the `<style>`.
- **Add a photo later:** if you decide to, add an `<img>` in the hero section and I can help style it.

---

## 🌐 Other free hosting options

If you ever want an alternative:

- **Netlify** — drag-and-drop `index.html` at https://app.netlify.com/drop. Instant free URL, no Git required.
- **Cloudflare Pages** — connect the GitHub repo at https://pages.cloudflare.com for a fast free `*.pages.dev` URL.
- **Vercel** — import the repo at https://vercel.com for a free `*.vercel.app` URL.

---

## 🔗 Custom domain (optional)

Once live on GitHub Pages, you can point a domain you own (e.g. `himanshusoni.dev`) at it via **Settings → Pages → Custom domain**. GitHub provides free HTTPS.

---

*Built as a single self-contained HTML file — fonts load from Google Fonts, everything else is inline. Works offline except for the web fonts.*
