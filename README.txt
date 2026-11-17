HOW TO SHIP
1. Netlify: drag this whole folder onto app.netlify.com/drop, or push it to GitHub and connect the repo.
2. GitHub Pages also works: push the folder contents to the repo root and turn on Pages.
3. Replace https://principleofdistinction.example in index.html with your real address (it appears in several tags). Nothing else needs editing.
ART: replace the placeholder files with yours, same names: favicon.ico 48x48, favicon-32.png, favicon-16.png, apple-touch-icon.png 180x180, icon-192.png, icon-512.png, icon-maskable-512.png (artwork in the centre 80%), og-image.png 1200x630.
MEDIA: put files in this folder and list them in media.json, e.g.
[{"type":"video","src":"intro.mp4","title":"Intro","note":"3 min"},{"type":"audio","src":"ep1.mp3","title":"Episode 1"}]
Big video: host on a CDN and use the full link as "src".
After any change, bump V='pod-v1' in sw.js to pod-v2 so phones refresh.
