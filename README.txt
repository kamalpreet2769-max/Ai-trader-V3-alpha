SIGNAL DESK - put it on your Android phone (about 5 minutes, no computer)

Start with Binance TESTNET (fake money). Do not use real money until you have
watched it for weeks and understand what it does.

1. Host the 5 files (index.html, manifest.webmanifest, sw.js, icon-192.png,
   icon-512.png) on a free HTTPS site. Easiest is GitHub Pages:
   - In Chrome on your phone, sign in at github.com (free account).
   - Tap + > New repository, name it signal-desk, set it Public, create it.
   - Tap "uploading an existing file", upload the 5 files, tap Commit.
   - Repository > Settings > Pages > Source: "Deploy from a branch",
     Branch: main, folder: / (root), Save.
   - After about a minute your app is at https://YOUR-NAME.github.io/signal-desk/
2. Open that link in Chrome, tap the menu (three dots) > "Install app"
   (or "Add to Home screen"). It now opens full-screen like a normal app.
3. Testnet keys: open https://testnet.binance.vision, sign in with GitHub,
   generate an HMAC-SHA-256 key. Paste key and secret into the app, tap Save.
4. Tap "Analyze & Trade". The app reads the chart; if it sees an edge it buys
   and places a stop-loss and take-profit on the exchange.

Keep your API key limited: enable only "Spot trading", never withdrawals.
The page stores your key in this browser only.
