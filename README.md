# RIZZ ME ⚡

> Can you make the AI blush?

A rizz-training game powered by the Claude AI API. Chat up AI personas, get scored on your rizz, climb the leaderboard, and battle friends in ranked 1v1s.

## 🚀 Deploy to GitHub Pages (3 steps)

1. **Create a new GitHub repo** — call it anything (e.g. `rizz-me`)
2. **Upload `index.html`** to the root of the repo
3. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` · Folder: `/ (root)`
   - Click **Save**

Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`

## 🔑 API Key

On first visit, the app will ask for your **Anthropic API key**.

- Get one at [console.anthropic.com](https://console.anthropic.com)
- Your key is stored **only in your browser** (localStorage) — never sent anywhere except directly to Anthropic
- Typical cost: ~$0.003 per conversation

## 📝 Notes

- **Leaderboard & Ranked mode** use localStorage, so scores are per-device (not shared globally like the original Claude artifact version)
- **Voice mode** requires Chrome or Edge (Web Speech API)
- **CORS**: The Anthropic API allows direct browser calls with the `anthropic-dangerous-direct-browser-access` header — this is enabled automatically

## 🗂 Files

| File | Purpose |
|------|---------|
| `index.html` | The entire app — single self-contained file |
| `README.md` | This file |
