# J.A.R.V.I.S. AI (Installable PWA)

Voice AI assistant with a half-robot / half-human face. Bolo ya type karo, JARVIS Hinglish me jawab deta hai.

## Features
- Installable PWA (Android, Windows, Mac, iPhone) with offline app shell
- API Keys box: **Groq, Gemini, OpenAI, Claude** (key + model + Test button + Primary AI select)
- Auto fallback: primary fail ho to baaki providers try hote hain
- Hinglish voice input and robotic voice output
- Keys sirf browser ke localStorage me rehti hain

## Install karne ka tareeka
1. Folder ko hosting par daalo (GitHub Pages / Netlify / Vercel). PWA ke liye **https** zaroori hai.
2. Link Chrome me kholo, **📲 Install App** button dabao (ya browser menu me "Install app").
3. iPhone: Safari > Share > Add to Home Screen.
4. App kholo, **🔑 API Keys** dabao, key daalo, **Test** dabao, **Save Keys**.

## GitHub Pages
1. Naya repo banao, in sab files aur `icons/` folder ko upload karo.
2. Settings > Pages > Source: `main` branch > Save.

## Files
`index.html`, `manifest.json`, `sw.js`, `icons/` (192, 512, maskable, apple-touch, favicon)

## Note
Local test ke liye `file://` par service worker nahi chalta. `python -m http.server` se kholo (localhost par PWA chalta hai).
