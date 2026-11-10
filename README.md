# Rangs Inventory ERP — GitHub Pages upload

This folder contains the self-contained static ERP prototype for GitHub Pages. No build step, package installation, database, or external runtime assets are required.

## Publish

1. Upload the files in this folder (`index.html`, `.nojekyll`, and this README) to the root of a GitHub repository, or upload `github-pages-upload.zip` and extract its contents into the repository root.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select your branch and **/(root)**, then save.
4. Open the Pages URL after deployment and hard refresh with **Ctrl+Shift+R**.

## Data note

This is a browser-only prototype. Its records are saved in localStorage in the current browser profile and do not sync between users or devices. Use a backend with authentication and a shared database before using real business records.
