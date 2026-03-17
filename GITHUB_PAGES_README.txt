GitHub Pages quick setup for this website

1. Create a new GitHub repository.
   Suggested name: mds-website-preview

2. Upload EVERY file inside this folder to the root of the repository.
   Important: index.html must stay at the repository root.

3. In the GitHub repository, go to:
   Settings -> Pages

4. Under Build and deployment:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
   - Save

5. Wait a few minutes for GitHub Pages to publish.

6. Your site URL will usually be:
   https://YOUR-USERNAME.github.io/REPOSITORY-NAME/

Notes:
- The .nojekyll file is included so GitHub Pages serves the static files directly.
- This site is a static HTML/CSS/JS site and does not need a backend to display.
- If you rename the repository, the final URL changes too.
