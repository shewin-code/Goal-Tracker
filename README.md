# Weekly Plan — PWA

A personal daily habit and training tracker. Installable as a Progressive Web App on iPhone or Android.

## Features

- Daily habit checklist (nutrition, skincare, hair, sleep)
- Pre-written 35-minute gym sessions (Push / Pull / Legs)
- Progress bar per day
- Week overview with completion percentages
- Fully offline — works with no internet after first load
- Data saved locally on your device (resets weekly)

## How to deploy (GitHub Pages)

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Your app will be live at `https://<your-username>.github.io/<repo-name>/`

## How to install on your phone

**iPhone (Safari):**
1. Open the GitHub Pages URL in Safari
2. Tap the Share button (box with arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add**

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the three-dot menu
3. Tap **Add to Home screen**
4. Tap **Add**

Once installed it opens fullscreen like a native app and works offline.

## File structure

```
/
├── index.html       # Main app
├── manifest.json    # PWA manifest
├── sw.js            # Service worker (offline support)
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## Notes

- Habit ticks reset each week automatically
- Ticks are saved in your browser's local storage — they stay if you close the app
- The app does not send any data anywhere — everything stays on your device
