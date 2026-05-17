# ⚙ SpeechFix — Vercel Setup

## Files
- `index.html` — the app
- `api/proxy.js` — keeps your API key server-side
- `vercel.json` — 30s timeout config

## Deploy Steps

1. Go to vercel.com → New Project → "Deploy without a Git repository"
2. Drag the entire `speechfix` folder into the upload area
3. Click Deploy — wait ~30 seconds
4. Go to: Project → Settings → Environment Variables
5. Add: `ANTHROPIC_API_KEY` = your key (from console.anthropic.com)
6. Go to: Deployments → click the three dots → Redeploy
7. Done — open your .vercel.app URL from any device

## Updating the App
1. Come back to Claude, describe what you want changed
2. Get the updated file
3. Vercel dashboard → your project → Settings → scroll to "Upload"
   (or drag new files in and redeploy)

## Adding Rules
Rules can be added live inside the app — no redeployment needed.
