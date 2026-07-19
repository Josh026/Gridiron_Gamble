# 🏈 Gridiron Gamble

A turn-based American football strategy game. Draft your roster, read defenses, call plays, and roll dice to determine outcomes.

## Getting Started

```bash
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) to play locally.

## Build for Production

```bash
npm run build
```

Output goes to `dist/` — deploy to Vercel, Netlify, or any static host.

## Deploy to Vercel

1. Push this repo to GitHub
2. Import the repo on [vercel.com](https://vercel.com)
3. Vercel auto-detects Vite — no config needed, just click Deploy

## How to Play

1. **Draft** — Pick 8 players (2S + 3A + 3B) across offense and defense
2. **Coin Toss** — Receive or kick
3. **Call Plays** — Pick an offensive play, optionally guess the defense for a stat boost
4. **Defense Calls** — Blitz, Zone, Man, Cover 2, or QB Spy
5. **Dice** — Offense die vs Defense die + luck modifier resolves the play
6. **Drive** — Earn first downs, manage 4th downs, score TDs

## Tech Stack

- React 18 + Vite
- Pure Web Audio API for sound
- Supabase for online multiplayer
