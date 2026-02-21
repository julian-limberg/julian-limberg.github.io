# Julian Limberg – Academic Website

A professional single-page academic website for Dr Julian Limberg, Senior Lecturer in Public Policy at King's College London.

## Files

```
github-pages/
├── index.html    ← Main website
├── style.css     ← All styling
└── README.md     ← This file
```

## How to publish on GitHub Pages

### Step 1 – Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create a free account).
2. Click **New repository**.
3. Name it exactly: `julianlimberg.github.io`
   *(replace `julianlimberg` with your GitHub username)*
4. Set it to **Public**.
5. Click **Create repository**.

### Step 2 – Upload the files

**Option A – Drag & Drop (easiest)**

1. Open your new repository on GitHub.
2. Click **Add file → Upload files**.
3. Drag `index.html` and `style.css` into the window.
4. Click **Commit changes**.

**Option B – Git command line**

```bash
cd path/to/github-pages
git init
git add index.html style.css
git commit -m "Initial website"
git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
git push -u origin main
```

### Step 3 – Enable GitHub Pages

1. Go to your repository **Settings → Pages**.
2. Under **Source**, select **Deploy from a branch**.
3. Choose **main** branch, folder **/ (root)**.
4. Click **Save**.

Your site will be live in ~1 minute at:
**`https://YOUR_USERNAME.github.io`**

---

## Optional: custom domain (e.g. julianlimberg.com)

1. Buy a domain from any registrar (Namecheap, GoDaddy, etc.).
2. In GitHub Pages settings, enter your custom domain.
3. Add a `CNAME` file to the repo containing just your domain name.
4. Point your domain's DNS to GitHub's IPs (instructions in GitHub Pages docs).

---

## Updating content

All content is in `index.html`. To update:
- Edit the file locally and re-upload, **or**
- Click the file on GitHub and use the pencil ✏️ edit button directly.

---

*Site built with plain HTML/CSS — no frameworks required.*
