# Static Website hosting with GitHub Pages

## Live Website
🔗 https://pooja-ja.github.io/github-pages/

## Objective
Deploy a simple HTML website for free using GitHub Pages.

## Repo includes
A static website made with HTML and CSS:
- `index.html`: the main page (the default file GitHub Pages loads)
- `style.css`: custom styling (colors, fonts, layout)

## Tools Used
- Git and GitHub
- GitHub Pages
- HTML and CSS

## Steps I Followed
1. Created `index.html` and `style.css` locally.
2. Initialized a Git repository and committed the files:
```bash
   git init
   git add .
   git commit -m "Add static website"
   git branch -M main
```
3. Created a new public repository on GitHub and pushed the code:
```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
```
4. Went to **Settings → Pages**.
5. Set Source to **Deploy from a branch**, selected branch **main** and folder **/ (root)**, then clicked **Save**.
6. Waited 1-2 minutes, then opened the live link GitHub provided.
7. Customized the look with CSS and pushed the changes, which redeployed automatically.

## How to Update the Site
Edit the files, then run:
```bash
git add .
git commit -m "Update site"
git push
```
GitHub Pages rebuilds and redeploys automatically.

## Key Learnings
- GitHub Pages hosts **static** content only (HTML, CSS, JS), with no server-side code.
- `index.html` in the root is the default file served.
- Every push to `main` triggers a new deployment.
- Custom domains are supported through Settings → Pages.