# Manda 纠正 — Mandarin Correction Engine

AI-powered Mandarin correction for **HSK 1–5** learners. Type or speak in English or Mandarin and get instant feedback on tones, grammar, vocabulary, and structure with a score out of 10.

---

## Features

- **English → Mandarin**: Translate your English to correct Mandarin
- **Correct my Mandarin**: Type or speak Mandarin and get it corrected
- **Scorecard**: Grammar, Tones, Vocabulary, Structure each scored /10
- **Breakdown table**: Side-by-side comparison of what you said vs correct
- **Voice input**: Speak directly via mic (Chrome/Edge)
- **Pronunciation**: Hear the correct Mandarin spoken back
- **History**: Last 5 corrections saved in your browser

---

## Live App

**[https://madhavigavade.github.io/Manda/](https://madhavigavade.github.io/Manda/)**

---

## How to Use

### Step 1: Get Your Free OpenRouter Key

1. Go to **[openrouter.ai](https://openrouter.ai)**
2. Click **Sign In** → Create account with Google or email (no credit card needed)
3. Go to **Settings → API Keys** (or direct link: [openrouter.ai/keys](https://openrouter.ai/keys))
4. Click **Create Key** → give it a name like "Manda" → Click **Create**
5. **Copy the key** (starts with `sk-or-...`) — it only shows once

### Step 2: Use the App

1. Open [https://madhavigavade.github.io/Manda/](https://madhavigavade.github.io/Manda/)
2. Paste your OpenRouter key in the **API Key** box → Click **Save**
3. Choose your mode — English to Mandarin or Correct my Mandarin
4. Type or speak your sentence
5. Click **Correct it**
6. Review your score and breakdown
7. Tap **Play pronunciation** to hear it

---

## Free Tier Details

**50 requests per day** on free tier (no credit needed)

To get **1,000 requests/day**:
- Add $5 credit to your OpenRouter account (once)
- Credits never expire

---

## Privacy

- Your API key is saved **only in your browser** (localStorage)
- No backend server — never sent anywhere except OpenRouter
- Correction history saved locally, not on any server
- No data collection or tracking

---

## Models Used

**Primary**: DeepSeek (if you add your DeepSeek key to OpenRouter BYOK)

**Free fallbacks** (if not using DeepSeek):
- Nemotron (550B)
- OpenAI GPT-OSS (20B)
- Google Gemma 4 (31B)

App auto-picks the best available model.

---

## Tech

- Pure HTML, CSS, JavaScript — no build needed
- Open-source AI via OpenRouter
- Web Speech API for voice input/output
- Noto Serif SC font for clean Hanzi display

---

## Version

v0.1

---

Built for Mandarin learners · Powered by open-source AI · No tracking, no ads
