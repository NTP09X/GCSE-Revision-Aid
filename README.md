# GCSE Revision Organiser

This is a GitHub Pages-ready version of the revision app.

## Publish steps
1. Create a new public GitHub repository.
2. Upload every file in this folder to the root of the repository.
3. In GitHub, open Settings -> Pages.
4. Under Build and deployment, choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /(root)
5. Save.
6. Wait a few minutes, then open:
   https://YOUR-USERNAME.github.io/YOUR-REPOSITORY-NAME/

## Important
- Keep all files together in the repo root.
- Replace index.html when you want to update the app UI.
- The app stores completed tasks in the browser on that device.

## Files
- index.html - app
- manifest.json - installable app config
- sw.js - offline caching
- .nojekyll - stops GitHub Pages from processing the site with Jekyll
- icon files - app icons
