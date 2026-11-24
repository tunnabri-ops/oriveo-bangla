# 💬 oriveo-bangla

[![AI Chat](https://img.shields.io/badge/type-ai%20chat-blue)](https://github.com/tunnabri-ops/oriveo-bangla)
[![Language](https://img.shields.io/badge/UI-Bangla%20%2B%20English-orange)](https://github.com/tunnabri-ops/oriveo-bangla)

**Multi-model Bangla AI chat — Groq, OpenRouter, Gemini, DeepSeek, Ollama / LM Studio / llama.cpp, with a free no-key fallback.**

> বাংলা সংস্করণ নিচে আছে। / Bangla version below.

## ✨ Features

- **Providers** (see `bangla-config.json`): Groq, OpenRouter, Gemini (free key), DeepSeek, Ollama / LM Studio / llama.cpp
- **Bangla + English** — language list includes `bn` and `en`
- **Free no-key fallback** — `text.pollinations.ai`, used only when you explicitly select it

## 🚀 How to use

```bash
npm install
npm run dev
```

Then open http://localhost:3000 and pick Bangla (bn) as the language.

## ⚠️ Honest limits

- Most provider APIs send **no CORS headers**, so static hosting will not run all models — a local / server run is the reliable path.
- The web client needs a server to run; it cannot be deployed as a static site as-is.

## 🇧🇩 বাংলা

**অরিভিও বাংলা — এক জায়গায় অনেক মডেলের বাংলা চ্যাট।**

- `npm install` তারপর `npm run dev` — http://localhost:3000 খুলুন
- ভাষা বাংলা (bn) সিলেক্ট করুন
- প্রোভাইডার ও ফ্রি fallback `bangla-config.json`-এ দেওয়া আছে

## 📄 License

MIT — use it however you like; credit is appreciated.
