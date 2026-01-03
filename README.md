# FILE: README.md

## Metriqa Legal Website

This repository hosts the official legal and transparency pages for the Metriqa app.
These pages are required for App Store submission and provide public access to
the Privacy Policy, Terms of Use, and Medical Disclaimer.

### Files
- index.html — Legal hub / landing page
- privacy.html — Privacy Policy (used in App Store Connect)
- terms.html — Terms of Use
- medical.html — Medical Disclaimer
- css/style.css — Shared Apple-style dark theme

### How to Deploy with GitHub Pages

1. Create a new GitHub repository (e.g. `metriqa-legal`)
2. Upload all files and folders exactly as-is
3. Go to **Repository Settings → Pages**
4. Source: **Deploy from a branch**
5. Branch: **main**
6. Folder: **/ (root)**
7. Save

GitHub will generate public URLs like:
- https://YOUR_USERNAME.github.io/metriqa-legal/
- https://YOUR_USERNAME.github.io/metriqa-legal/privacy.html
- https://YOUR_USERNAME.github.io/metriqa-legal/terms.html
- https://YOUR_USERNAME.github.io/metriqa-legal/medical.html

### App Store Connect
Paste the **privacy.html URL** into:
App Store Connect → App Information → Privacy Policy URL

No app code changes required.
