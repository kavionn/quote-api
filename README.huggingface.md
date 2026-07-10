---
title: Quote API
emoji: 💬
colorFrom: indigo
colorTo: purple
sdk: docker
pinned: false
license: mit
short_description: Quote image generation API for Telegram bots
---

# Quote API

REST API untuk generate gambar quote, digunakan oleh Telegram bot.

## Endpoint

```
POST /generate
GET  /health
```

## Environment Variables (Secrets)

| Nama | Keterangan |
|---|---|
| `BOT_TOKEN` | Token bot Telegram (untuk bypass rate limit) |
| `EMOJI_DOMAIN` | Domain emoji (default: `https://emojipedia.org/`) |

> Port yang digunakan: **7860** (wajib untuk HF Spaces Docker).
