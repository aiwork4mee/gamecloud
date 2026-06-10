# GameCloud 🎮

> The free browser arcade — Upload, Play, Dominate the Vault.

A fully self-contained single-page HTML5 gaming community where anyone can upload, share, and play HTML-based games directly in the browser.

## Deploy in 60 seconds

### Vercel (Recommended — Fastest)
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. **Framework Preset:** Other  
4. **Root Directory:** leave as `.`  
5. Click **Deploy** — done ✅

### Render (Static Site)
1. Push to GitHub
2. Go to [render.com](https://render.com) → New → Static Site
3. Connect your repo
4. **Publish directory:** `.` (just a dot)
5. Click **Create Static Site** — done ✅

### Netlify (Drag & Drop — No GitHub needed)
1. Go to [netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire `gamecloud-deploy` folder onto the page
3. Done in 10 seconds ✅

### GitHub Pages
1. Push to a GitHub repo
2. Settings → Pages → Source: Deploy from branch `main`, folder `/` (root)
3. Done ✅

## Features
- 🎮 Upload & play HTML5 games in sandboxed iframes
- ⭐ Community ratings (1–5 stars)
- 🔥 One hype/like per game per user
- 🏆 Leaderboards (Top Rated, Most Played, Trending, New)
- 👤 Edit profile with emoji avatar
- 💬 Game lobby comments
- 📱 Mobile-responsive with bottom nav
- 💾 All data stored in localStorage (no backend needed)

## Files
- `index.html` — The entire app (self-contained, ~130KB)
- `vercel.json` — Vercel routing config
- `render.yaml` — Render static site config
- `_redirects` — Netlify redirect rules
- `package.json` — Optional, for Render web service
