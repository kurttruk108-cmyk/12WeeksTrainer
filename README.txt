Trainer web version

Open this app from a web address, not by opening index.html directly from the iPhone Files app. Safari blocks or limits local file storage and media access.

Quick local preview on a computer:
1. Open PowerShell in this folder.
2. Run: python -m http.server 8000
3. Open http://localhost:8000 in a computer browser.

To use it on iPhone, upload the entire web folder (including the videos folder) to any static web host such as GitHub Pages, Netlify, or Cloudflare Pages, then open the published HTTPS URL in Safari. Use Share > Add to Home Screen if you want it to behave like an app.
