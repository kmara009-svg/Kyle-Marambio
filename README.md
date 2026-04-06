[README.md](https://github.com/user-attachments/files/26503419/README.md)
# Kyle Marambio — Portfolio Website

A personal portfolio site for GitHub Pages built with plain HTML and CSS. No frameworks, no build tools — just upload and it works.

## How to put this on GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create an account)
2. Click the **+** in the top-right → **New repository**
3. Name it: `your-username.github.io` (replace `your-username` with your actual GitHub username)
   - Example: `kylemarambio.github.io`
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the files

**Option A — Drag and drop (easiest):**
1. Open your new empty repository on GitHub
2. Click **"uploading an existing file"**
3. Drag `index.html` into the upload box
4. Click **Commit changes**

**Option B — GitHub Desktop (recommended if you plan to update it often):**
1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your new repo
3. Copy `index.html` into the repo folder
4. Commit and push

### Step 3 — Enable GitHub Pages

1. In your repository, go to **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose **main** branch, **/ (root)** folder
4. Click **Save**
5. Wait ~1 minute — your site will be live at `https://your-username.github.io`

---

## Customising your site

### Add your own photo (hero section)
Replace the grey placeholder in the `hero-right` div with:
```html
<img src="your-photo.jpg" alt="Kyle Marambio" />
```
Upload `your-photo.jpg` alongside `index.html` in your repository.

### Add your LinkedIn URL
Find this line and replace the `href`:
```html
<a href="https://linkedin.com" target="_blank" class="linkedin-btn">
```

### Set up the contact form (free)
1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form — you'll get an ID like `xpzgabcd`
3. In `index.html`, find this line and replace `your-form-id`:
```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

### Update portfolio cards
Each project card looks like:
```html
<div class="portfolio-card">
  <img src="your-image.jpg" alt="Description" />
  <div class="portfolio-card-info">
    <p class="portfolio-card-tag">Your Category</p>
    <p class="portfolio-card-title">Project Title</p>
    <p class="portfolio-card-desc">Short description.</p>
  </div>
</div>
```
Replace the image `src` with your own photos and update the text.

---

## File structure

```
your-username.github.io/
  index.html      ← the whole site (everything is in here)
  your-photo.jpg  ← add your own photo
  README.md       ← this file (optional on GitHub)
```

---

Built with ❤️ for Kyle Marambio · Exercise & Sport Science
