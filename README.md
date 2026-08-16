# 📚 BookBreak — Understand Any Book in Minutes

Type a book name → get a complete breakdown powered by Google's **free Gemini AI**: one-sentence idea, 60-second summary, big picture, main ideas, takeaways, characters/core concepts, quotes, "should you read it," and book-club questions.

## ✨ Features
- 🔍 **Break a Book** — title + optional author → full structured breakdown (~15 sec)
- 📚 **My Library** — every breakdown auto-saves on your device, reopen anytime
- ⧉ **Copy anything** — per-section copy buttons + "Copy full breakdown" (paste into Google Docs!)
- ⤓ Backup / ⤒ Restore — move your library between devices
- Works with fiction & nonfiction; book covers pulled free from Google Books

## 🔑 Setup (one time, $0)
1. Go to [aistudio.google.com](https://aistudio.google.com) → **Get API key** → **Create API key**
2. Open the app's **⚙️ Setup** tab → paste the key → Save
3. That's it. The key stays in your browser's local storage; free tier is ~1,000+ requests/day.

## 🚀 Run locally
Open `index.html` in a browser, or:
```bash
cd bookbreak
python3 -m http.server 8002
```

## 📤 GitHub & ▲ Vercel
Static site, zero build. Same recipe as the sister apps:
```bash
git init && git add . && git commit -m "BookBreak: AI book breakdowns"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/bookbreak.git
git push -u origin main
```
Then import at [vercel.com/new](https://vercel.com/new) (Framework: Other).

> Note: BookBreak generates AI study notes for understanding books — it's a helper for learning, not a substitute for reading. 💜

## Sister apps
- 🎬 UGC HQ — [ugc-hq.vercel.app](https://ugc-hq.vercel.app)
- 📸 Shoot Day — [shoot-day.vercel.app](https://shoot-day.vercel.app)
