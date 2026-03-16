# 🧠 PsycheAI — Psychology Book Assistant

A generative AI assistant that answers questions **strictly from your uploaded psychology PDFs**.  
Powered by **LLaMA 3.3 70B** via [Groq](https://console.groq.com) — free and open source.

🔗 **Live Demo:** `https://YOUR_USERNAME.github.io/psycheai`

---

## Features

- 📚 Upload any psychology PDF books
- 🔍 AI answers **only** from your uploaded texts — zero hallucination
- ❌ Returns **"No data found"** if topic is absent from books
- 🆓 Uses Groq's free API (LLaMA 3.3 70B)
- ⚡ No backend needed — runs entirely in the browser

---

## How to Use

1. Get a **free Groq API key** at [console.groq.com](https://console.groq.com)
2. Open the app and paste your key in the sidebar
3. Upload psychology PDF books
4. Ask any question — answers come only from your books

---

## Deploy Your Own

```bash
# 1. Fork this repo on GitHub
# 2. Go to Settings → Pages → Source: main branch / root
# 3. Your site will be live at https://YOUR_USERNAME.github.io/psycheai
```

---

## Tech Stack

- Vanilla HTML / CSS / JavaScript (zero dependencies)
- [PDF.js](https://mozilla.github.io/pdf.js/) for PDF text extraction
- [Groq API](https://console.groq.com) — LLaMA 3.3 70B (free tier)

---

## Anti-Hallucination System

The AI is instructed with 6 strict rules:

| Rule | Description |
|------|-------------|
| Source Only | Answer only from uploaded book text |
| No Data Found | Returns exact phrase if topic is absent |
| Keyword Check | Verifies terms exist before answering |
| No Invention | No inference or gap-filling allowed |
| Partial Data | Notes when only partial info is found |
| Direct Quotes | May quote passages from the text |

---

## License

MIT — free to use, modify, and deploy.
