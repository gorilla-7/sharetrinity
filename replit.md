# Project

This is a static HTML page. It redirects visitors to `https://www.google.com`, preserving the URL fragment (the part after `#`).

## Preview

Use the **Start application** workflow. It runs `python3 -m http.server 5000 --bind 0.0.0.0` to preview the existing page. No packages or secrets are required.

## Publish

Publishing uses Replit's Static deployment with the project root (`.`) as the public directory. No build command is needed. Click **Publish** to make the page live.

The redirect happens immediately, so the preview navigates away from this page. The original HTML and redirect behavior are unchanged.
