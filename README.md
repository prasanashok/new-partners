Averson Search Partners — Static site

This repository contains a simple static landing page (index.html + styles.css).
You can deploy this to Netlify as a static site.

Notes:

Replace the Calendly URL(s) and the contact form placeholder with your real links/shortcode.
The site uses only the provided CSS and system fonts (no external font loads).
How to deploy

Commit & push these files to your GitHub repository.
On Netlify:
Option A (connect repo): In Netlify UI choose "New site from Git", connect your GitHub account and select this repo. Build command: (leave blank). Publish directory: / (root).
Option B (drag & drop): Build a zip of the site (index.html + styles.css) and drop it on Netlify Drop.
After deploy, Netlify will give you a site URL. Configure a custom domain if needed.
Local preview

Open index.html in your browser.
Or run a simple local server:
Python 3: python -m http.server 8000 then open http://localhost:8000
Node (if you have serve): npx serve . and open the printed URL.
