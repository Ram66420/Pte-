
# PTE Core Practice (Unofficial)

A fully working practice site for PTE Core with basic AI-style marking using local heuristics and browser speech recognition (when available). **No external API keys required.**

## Quick start
```bash
npm install
npm run dev
# open http://localhost:3000
```

## Build (with fresh 120+ items)
```bash
npm run generate:items
npm run build
npm start
```

### Notes
- Speaking uses the browser **Web Speech API** for STT. Works best in Chrome. If unavailable, fluency is scored from audio duration and silence; content scoring is limited.
- All items are **originally generated** by the local generator script. Admin can add/edit in the Admin page and export/import JSON.
