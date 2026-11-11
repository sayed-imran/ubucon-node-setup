# Scaling Local AI: Benchmarking vLLM and Building Personal Agents

Pre-setup page for the UbuCon India 2026 workshop by **Sayed Imran** (15 Nov 2026, 15:35–16:35 IST, Workshop Room, Bengaluru, AI/ML track).

Session page: https://events.canonical.com/event/157/contributions/1091/

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
