# UbuCon India workshop: Node.js setup page

A single-page guide (`index.html`) that walks attendees through installing **nvm** and **Node.js 22.23.2** on Ubuntu, Windows 11 (Windows 10 is not supported; optional WSL) and macOS.

## Publish on GitHub Pages

1. Create a new public repo on GitHub, e.g. `ubucon-node-setup`.
2. Push this folder:
   ```bash
   git init
   git add .
   git commit -m "Add workshop setup page"
   git branch -M main
   git remote add origin https://github.com/<your-username>/ubucon-node-setup.git
   git push -u origin main
   ```
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, branch `main`, folder `/ (root)`, Save.
4. After a minute the page is live at `https://<your-username>.github.io/ubucon-node-setup/`.
