# Manda 纠正 — Mandarin Correction Engine

> AI-powered Mandarin correction for HSK 1–5 learners.  
> Type or speak in English or Mandarin and get instant feedback on tones, grammar, vocabulary, and structure — scored out of 10.

**Live App → [https://madhavigavade.github.io/Manda/](https://madhavigavade.github.io/Manda/)**

---

## What It Does

| Feature | Details |
|---|---|
| **English → Mandarin** | Corrects your English first, then translates to Mandarin |
| **Correct my Mandarin** | Fixes tones, grammar, measure words, word order |
| **Scorecard** | Grammar, Tones, Vocabulary, Structure each scored /10 |
| **Dual Breakdown** | Separate English and Mandarin correction tables |
| **HSK Level Detection** | Tells you which HSK level your sentence is |
| **Voice Input** | Speak your sentences, text accumulates across recordings |
| **Pronunciation** | Hear the corrected Mandarin spoken back |
| **Multi-Provider** | OpenRouter Free, GPT, Claude, DeepSeek support |
| **History** | Last 5 corrections saved in your browser |

---

## How to Use

### Step 1 — Get a Free OpenRouter Key

1. Go to **[openrouter.ai](https://openrouter.ai)**
2. Sign up — Google or email, no credit card needed
3. Go to **Settings → API Keys** → **[openrouter.ai/keys](https://openrouter.ai/keys)**
4. Click **Create Key** → name it "Manda" → Create
5. Copy the key — starts with `sk-or-...` (shown only once)

---

### Step 2 — Set Up the App

1. Open **[https://madhavigavade.github.io/Manda/](https://madhavigavade.github.io/Manda/)** in Chrome or Edge
2. Under **AI Provider** → select **OpenRouter Free (Recommended)**
3. Paste your `sk-or-...` key in the **API Key** box
4. Click **Save** — you'll see a green ✓ Connected chip
5. Your key is saved in your browser — you only do this once

---

### Step 3 — Choose Your Mode

| Mode | Use When |
|---|---|
| **English to Mandarin** | You want to say something in Mandarin but write it in English first |
| **Correct my Mandarin** | You already wrote or spoke Mandarin and want it checked |

---

### Step 4 — Type or Speak

**Typing:**
- Click the **Type** tab
- Type your sentence — supports 10+ sentences at once
- Paste text directly from notes or documents

**Speaking (Chrome/Edge only):**
- Click the **Speak** tab
- Tap the mic button → speak your sentence → mic stops automatically
- Your spoken text appears in the box
- Tap mic again to **add more sentences** — text accumulates, nothing is lost
- Tap **✕ Clear all text** to start fresh

---

### Step 5 — Get Your Correction

1. Click **Correct it**
2. Wait a moment — longer inputs take a few seconds
3. Review your results:

**English to Mandarin Mode shows:**
- ✅ Corrected English (grammar, spelling, punctuation fixed)
- ✅ Corrected Mandarin (Hanzi + Pinyin)
- ✅ English Breakdown table (what was wrong in your English)
- ✅ Mandarin Breakdown table (how the translation was constructed)
- ✅ Overall score /10 with ring gauges
- ✅ HSK level badge

**Correct my Mandarin Mode shows:**
- ✅ Corrected Hanzi + Pinyin
- ✅ Breakdown table (tones, grammar, measure words, word order)
- ✅ Overall score /10 with ring gauges
- ✅ HSK level badge
- ✅ What you got right
- ✅ More natural alternative phrasing

4. Click **▶ Play pronunciation** to hear the correct Mandarin

---

### Step 6 — Review History

- Your last 5 corrections appear at the bottom
- Click any item to view that result again

---

## Using BYOK Providers (Optional)

If you have your own GPT, Claude, or DeepSeek API key you can use it through OpenRouter.

### OpenAI GPT

1. Get key at **platform.openai.com/api-keys**
2. Add to OpenRouter at **openrouter.ai/settings/byok** → Select OpenAI → Paste key → Save
3. In Manda → Select **OpenAI GPT (BYOK)** from provider dropdown
4. Enter your OpenRouter key → Save

### Anthropic Claude

1. Get key at **console.anthropic.com/api-keys**
2. Add to OpenRouter at **openrouter.ai/settings/byok** → Select Anthropic → Paste key → Save
3. In Manda → Select **Anthropic Claude (BYOK)** from provider dropdown
4. Enter your OpenRouter key → Save

### DeepSeek

1. Get key at **platform.deepseek.com/api-keys**
2. Add to OpenRouter at **openrouter.ai/settings/byok** → Select DeepSeek → Paste key → Save
3. Enable **Always use for this provider** → ON
4. In Manda → Select **DeepSeek (BYOK)** from provider dropdown
5. Enter your OpenRouter key → Save

---

## Free Tier Limits

| Plan | Requests/day |
|---|---|
| OpenRouter Free (no credit) | 50/day |
| OpenRouter + $5 credit | 1,000/day |
| BYOK (GPT/Claude/DeepSeek) | Your own provider limits |

Credits on OpenRouter never expire.

---

## HSK Scope

| Level | What's covered |
|---|---|
| HSK 1-2 | Basic SVO structure, negation, measure words, question particles |
| HSK 3 | Ba sentences, bi comparisons, aspect particles le/guo/zhe |
| HSK 4 | Complex ba/bei, conjunctions, potential complements, shi...de |
| HSK 5 | Chengyu, formal written Chinese, complex clauses, passive constructions |

---

## Browser Support

| Browser | Type | Speak |
|---|---|---|
| Chrome (Desktop) | ✅ | ✅ |
| Edge (Desktop) | ✅ | ✅ |
| Chrome (Mobile) | ✅ | ✅ |
| Firefox | ✅ | ❌ |
| Safari | ✅ | ❌ |

Mic requires Chrome or Edge. All other features work in any browser.

---

## Privacy

- Your API key is saved **only in your browser** (localStorage)
- No backend server — API calls go directly from your browser to OpenRouter
- No data collection, no tracking, no ads
- Correction history stored locally in your browser only

---

## Tech Stack

- Pure HTML, CSS, JavaScript — no framework, no build step
- Open-source AI models via OpenRouter
- Web Speech API for voice input and pronunciation
- Google Fonts — Noto Serif SC for clean Hanzi display
- Deployable on GitHub Pages — no server needed

---

## Version

**v0.2** — Multi-provider support, dual breakdown tables, voice accumulation, 10+ sentence support

---

Built for Mandarin learners · Powered by open-source AI · No tracking, no ads
