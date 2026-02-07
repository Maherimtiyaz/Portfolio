# GitHub Pages Deployment Guide

## Method 1: Upload via GitHub Website (Recommended for Beginners)

1. Go to https://github.com/Maherimtiyaz
2. Click "+" → "New repository"
3. Repository name: `Maherimtiyaz.github.io` (or `portfolio`)
4. Set to Public
5. Click "Create repository"
6. Click "uploading an existing file"
7. Drag these files:
   - index.html
   - styles.css
   - script.js
   - README.md
8. Click "Commit changes"

## Method 2: Using Git Commands

Open terminal/command prompt in your portfolio folder and run:

```bash
git init
git add .
git commit -m "Initial portfolio deployment"
git branch -M main
git remote add origin https://github.com/Maherimtiyaz/YOUR-REPO-NAME.git
git push -u origin main
```

Replace `YOUR-REPO-NAME` with your actual repository name.

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Click "Pages" in the left sidebar
4. Under "Source":
   - Select branch: **main**
   - Select folder: **/ (root)**
5. Click "Save"
6. Wait 1-2 minutes
7. Your site will be live at: `https://Maherimtiyaz.github.io/YOUR-REPO-NAME/`

## If you named it `Maherimtiyaz.github.io`:
Your site will be at: `https://Maherimtiyaz.github.io/`

## Updating Your Portfolio

Whenever you make changes:
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon (Edit)
4. Make changes
5. Scroll down and click "Commit changes"
6. Wait 1-2 minutes for changes to go live

---

## Alternative: Deploy to Netlify (Even Easier!)

1. Go to https://app.netlify.com/drop
2. Drag your entire portfolio folder onto the page
3. Get instant live link (e.g., `random-name-123.netlify.app`)
4. Free custom domain available!

**Netlify is faster but GitHub Pages is more professional for developers.**

Choose whichever you prefer!
