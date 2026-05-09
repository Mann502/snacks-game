# Snacks and his Big Adventure

A side-scrolling browser game starring **Snacks**, a brown Cavapoo with floppy black ears.

## ▶ Play it on your phone

Once deployed, open this URL on your phone:

**https://mann502.github.io/snacks-game/**

Tip: open it in Safari/Chrome and use **"Add to Home Screen"** to get a fullscreen icon you can tap any time.

### First-time setup (one-off, by repo owner)

The site is published via a GitHub Actions workflow (`.github/workflows/pages.yml`) that runs on every push to `main`. To turn it on:

1. Merge the dev branch into `main`.
2. In the repo: **Settings → Pages → Source: "GitHub Actions"**.
3. Wait ~30 seconds for the first deploy under the **Actions** tab. The URL above will go live.

## How to play

- **Tap / Click / Space** — jump
- **Hold** — jump higher
- Dodge **bins**, **trees**, and **flying birds** — each hit costs a life
- **Catch tennis balls** in your mouth to gain a life (and bonus points)
- Lives start at 3, max 5. Game ends at 0.

## Run locally

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

Everything is rendered with the HTML5 canvas — no images, no dependencies.
