# VOXLY — Voice Translator

A minimal, futuristic web app for **live voice → text → translation → voice**, with saved sessions and AI summaries. Built for Gen Z.

## Features

- **Live voice to text** — continuous speech recognition (Web Speech API)
- **Live translation** — chunks translate as you speak (MyMemory API)
- **Text to voice** — hear original or translated text aloud
- **Saved sessions** — lessons autosave in browser localStorage
- **AI summary** — optional Claude or OpenAI summary of any session
- **Export** — download transcript, translation, summary, or audio (.webm)
- **Backup** — export all sessions as JSON

## Design

Deep blue + metallic silver palette, Michroma display font, glass-morphism UI, ambient grid background.

## Local use

Open `voice-to-text-translator.html` in **Chrome** or **Edge**.

```bash
npx serve .
```

## Deploy to Vercel

1. Push this repo to GitHub: [github.com/yunesinjust/voxly-voice-translator](https://github.com/yunesinjust/voxly-voice-translator)
2. Go to [vercel.com/new](https://vercel.com/new) and import the repo
3. Deploy — no build step needed

## Browser notes

- **Speech recognition**: Chrome / Edge (desktop & Android)
- **Speech synthesis**: all modern browsers
- **Microphone**: HTTPS required in production (Vercel provides this)

## License

MIT
