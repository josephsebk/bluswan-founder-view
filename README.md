# Founder App

This folder contains the standalone Founder View application.

## How to Host
You can deploy this folder (`founder-app`) to any static hosting service:
- **Vercel / Netlify**: Drag and drop this folder into their deployment UI, or connect a git repo and set the "Root Directory" to `founder-app`.
- **GitHub Pages**: Configure your repository to serve from this folder (if possible) or a separate branch.
- **S3 / GCS**: Upload the contents of this folder to your bucket.

## Files
- `index.html`: The main entry point (renamed from `founder.html`).
- `assets/`: Contains images and the mapping script.

## Updates
If you update investor images in the main app, remember to copy the new `assets/` folder here.
