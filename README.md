# VOXLY — Voice Translator

A minimal, futuristic web app that converts **voice → text → translation → voice**, built for Gen Z.

## Features

- **Voice to text** — speak in your language using the browser mic (Web Speech API)
- **Translate** — convert text to 20+ languages via MyMemory Translation API
- **Text to voice** — hear the original or translated text aloud
- **Save** — download a `.txt` file with both original and translated text
- **Copy** — one-click clipboard copy

## Design

Blue + metallic silver palette, Michroma display font, glass-morphism UI, ambient grid background.

## Local use

Open `voice-to-text-translator.html` in **Chrome** or **Edge** (speech recognition requires a Chromium browser).

Or serve locally:

```bash
npx serve .
```

## Deploy to Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repo — Vercel auto-detects static files
4. Deploy — no build step needed

## Browser notes

- **Speech recognition**: Chrome / Edge (desktop & Android)
- **Speech synthesis**: all modern browsers
- **Microphone**: HTTPS required in production (Vercel provides this automatically)

## License

MIT
