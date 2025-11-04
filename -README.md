# GitHub Pages Starter

This repository is ready to publish on **GitHub Pages**.

## What’s inside
- `index.html` — your homepage (header, intro, placeholder links)
- `style.css` — minimal styling
- `README.md` — these instructions

## Publish (Web UI, easiest)
1. Create a repo on GitHub (either `username.github.io` for a personal site, or any name for a project site).
2. Upload these three files to the repository root.
3. Go to **Settings → Pages**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` (or your default)
   - **Folder**: `/ (root)`
4. Click **Save**. In a minute, your site will be live at the URL GitHub shows there.

## Publish (Command line)
```bash
git init
git add .
git commit -m "Initial commit: GitHub Pages starter"
git branch -M main
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
```
Then enable Pages under **Settings → Pages** as above.
