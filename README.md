# Previewing `main.pug` and `main.scss`

Quick setup to compile Pug -> HTML and Sass -> CSS and run a live-reloading preview.

Prerequisites
- Node.js (LTS) installed: https://nodejs.org

Install dev dependencies (from project folder):
```powershell
cd C:\Users\suii\Desktop\birthday
npm install --save-dev pug-cli sass live-server concurrently
```

Commands
- Compile once: `npm run pug` and `npm run sass`
- Watch and serve (recommended): `npm run dev`

What `npm run dev` does
- Watches `main.pug` and outputs `main.html` when changed.
- Watches `main.scss` and outputs `main.css` when changed.
- Starts `live-server` and opens `main.html` in the browser with live reload.

If your Pug uses includes/partials, `pug --watch . --out .` may be preferable.
