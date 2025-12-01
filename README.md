# JioTV-Web  
Watch live Indian TV channels in any browser – hosted **100 % free** on GitHub Pages.

## Features
- Grid of 600+ channels (auto-fetched from JioTV)
- Search box
- YouTube-styled player (Shaka-Player) with DRM support
- Works on desktop, Android, iOS (Safari), TV browsers

## One-time deploy (≤ 2 min)
1. Click ► **“Fork”** (top-right) – or download & unzip this repo  
2. Repo ► Settings ► Pages ► Source = `main` branch / root ► Save  
3. GitHub gives you a green link:  
   `https://YOUR-USERNAME.github.io/JioTV-Web`  
4. **Done** – open the link; channels load instantly.

## CORS fix (only if streams fail)
GitHub Pages sends no `Access-Control-Allow-Origin` header.  
Add a **free Cloudflare proxy** in 30 s:

1. Cloudflare ► “Add site” ► type `YOUR-USERNAME.github.io`  
2. Finish wizard (ignore nameserver change – you don’t own the domain)  
3. Rules ► Transform Rules ► Modify Response Header  
   - If hostname equals `YOUR-USERNAME.github.io`  
   - Add ▸ `Access-Control-Allow-Origin` = `*`  
4. Deploy. Streams now play everywhere.

## File map
