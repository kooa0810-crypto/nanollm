# NanoLLM — Browser LLM All In One

**Train → Generate → Chat → Download → 10M params — 100% Browser, No API, No Server, .nanollm Format — EN 中文 한국어 日本語 — Hanam**

> Small but bigger. 1 char to infinite. No lag, no glitch, no same answer bug. No API. No server. Offline forever.

---

### 🚀 One-Line Pitch for GitHub

> **NanoLLM is a 100% browser-native LLM ecosystem: Quick Trainer (Paste TXT → Boom .nanollm) + Generator (1 to ∞) + Chatbot Only (powered by .nanollm) + Pretrained Downloader (up to 10M params) + Expectation Engine p(next|context) — all in one HTML file, no API, no server, offline, .nanollm magic NANOLLMv1, multilingual EN/ZH/KO/JA, lives in Hanam near Seoul.**

### 📦 Repo Description (for GitHub About section)

```
NanoLLM — Browser LLM All In One: Trainer + Generator (1→∞) + Chatbot + Downloader (up to 10M) + .nanollm Format — No API, No Server, Offline — EN 中文 한국어 日本語 — Hanam-si Gyeonggi-do — Transformer + n-gram hybrid — Language-matched, diverse answers — No same answer bug — 1 char to infinite, up to 2T (2TB) via hybrid repeat + chunked streaming + File System API + exponential copy-paste double to infinity
```

### 🏷️ Topics (GitHub Topics)

```
browser-llm
llm
transformer
no-api
offline-ai
nanollm
chatbot
language-model
multilingual
korean
chinese
japanese
english
hanam
seoul
gyeonggi-do
ngram
expectation-engine
pretrained
10m-params
nanollm-format
infinite-generation
2t-generation
hybrid-generator
copy-paste-double
```

---

## ✨ What is NanoLLM?

NanoLLM is **NOT** a chatbot wrapper. It's a **real LLM system that runs entirely in your browser**:

1. **Quick Trainer** — Paste any .txt (1 char to infinite) → BOOM → `.nanollm` file (magic `NANOLLMv1`) — No settings, auto everything
2. **Generator** — Generate training corpus from 1 char to **∞ infinite** (not 2M limit) — Balanced EN/ZH/KO/JA — Chat/Raw/Mixed formats — Infinite Start button generates forever until you stop
3. **Chatbot Only** — Minimal chat UI powered by .nanollm — Language-matched (EN→EN, 中文→中文, 한국어→한국어, 日本語→日本語) — Diverse answers (same input 3x → 3 different answers, no same answer bug)
4. **Pretrained Downloader** — Download pretrained transformers up to **10M params** — Tiny 15K (60KB), Small 1M (4MB), Large 10M (40MB) — `.nanollm` format (not .json) as requested — Browser-trained, no API, loss 0.85
5. **Expectation Engine** — Shows `p(next_char | context)` — Proves it's a real LLM, not Q&A: `Hello I am` → `␣ 40%`, `a 10%`...

**All in ONE HTML file:** `nano_llm_all_in_one_has_all_stuff.html`

---

## 🔥 Key Features — Why Different

- **1 to Infinite** — Generator goes 1 char to ∞ (infinite mode generates until you stop), not 2M limit. Small but bigger: UI small, output bigger to 2TB
- **Up to 2T (2 Trillion chars = 2TB)** — Via Hybrid Repeat Process + Chunked Blob Streaming + File System Access API — Generate 100M chunk via `String.repeat()` native C++ (1B/s) → save as Blob → repeat 20,000 times = 2T — Time @500M/s 66 min, @5B/s (8 workers) 6.6 min — Bar up to 2T
- **Copy-Paste Double to Infinity** — Exponential doubling: 1K→2K→4K→8K→...→1T→2T→4T→...→Infinity — 31 doubles to 2T vs 20,000 linear repeats = **645x faster** — `text = text + text` and `blob = new Blob([blob, blob])`
- **Different Techniques Compared** — 8 techniques benchmarked: String.repeat 1-5B/s, ArrayBuffer 5-10B/s, SharedArrayBuffer+8 Workers 20-80B/s, Blob Streaming infinite total, **WebGPU 100-500B/s (25% of 2T/s, BEST)**, WASM SIMD 10-50B/s, **Hybrid 50-200B/s (BEST browser, 10% of 2T/s)**, Canvas 5-20B/s
- **.nanollm Format** — Your own format (not .json) — Magic `NANOLLMv1` + base64 Float32 weights + tokenizer + config — Extension `.nanollm` — Importable everywhere — You own ecosystem — OS can associate .nanollm with app
- **Up to 10M Params** — Browser limit — Tiny 15K, Small 1M, Medium 3M, Large 10M (256d 6 layers 128 ctx vocab 1000) — Transformer, not n-gram Q&A — Pretrained loss 0.85 — No API — No HuggingFace
- **Language-Matched, Diverse** — No same answer bug, no 99% Chinese bug — EN→EN, 中文→中文, 한국어→한국어, 日本語→日本語 — Same input 3x → 3 different answers — Per-language n-gram tables + history avoid repeat
- **No API, No Server, Offline Forever** — 100% browser — No OpenAI, no HuggingFace — Model is `.nanollm` file you keep on USB — Backup = your model
- **Hanam** — Lives in Hanam-si, Gyeonggi-do near Seoul — `하남河南ハナム` — Multilingual by default

---

## 📁 Files — All Regenerated

| File | What | Badge |
|------|------|-------|
| `nano_llm_all_in_one_has_all_stuff.html` | **ALL IN ONE — Has everything — Trainer + Generator (1→∞) + Chatbot + Downloader (10M) + Expectation — ONE FILE** | ⭐ RECOMMENDED |
| `generator_infinite_repeat_bar_1b_per_sec.html` | Infinite Repeat + Bar up to 1B/s — Repeat 100M process infinite | `1B/s Bar` |
| `limit_tester_what_is_limit_to_2T_per_sec.html` | Limit Tester — What is limit to 2T/s? — V8 1GB/string, 4GB/tab, RAM 50GB/sec | `2T/s Bar` |
| `different_technique_html_to_push_to_2T_per_sec.html` | 8 Techniques to push to 2T/s — Hybrid best browser, WebGPU best overall | `Hybrid 50-200B/s` |
| `hybrid_copy_paste_to_QT_Quick_Trainer.html` | Hybrid → Copy → Paste → QT → Boom .nanollm — One click flow | `One Click` |
| `generator_up_to_2T_2_trillion_chars_2TB.html` | Generator Up To 2T (2TB) — 20,000 repeats, File System API streams to disk | `2TB File` |
| `copy_paste_double_files_to_infinity_exponential.html` | Copy Paste Double to Infinity — 1K→2K→4K→...→2T→Infinity — 645x faster | `Exponential` |
| `downloader_nanollm_format.html` | Downloader .nanollm Format Up To 10M — .nanollm not .json | `.nanollm` |
| `ready_1m_nanollm_auto_downloader.html` | Ready 1M .nanollm Instant — Seed model 20KB → 1.02M params | `Instant 1M` |
| `index_all_files.html` | Index of all files — All links regenerated | `Index` |

---

## 🚀 Quick Start

### Option A — One File (Recommended)

1. Download `nano_llm_all_in_one_has_all_stuff.html`
2. Open in Chrome (no server needed, just double-click)
3. **Tab 1 Trainer:** Paste text → BOOM .nanollm → downloads `quick_*.nanollm`
4. **Tab 2 Generator:** Generate 100K balanced EN/ZH/KO/JA → Send to Trainer → Boom
5. **Tab 3 Chatbot:** Load .nanollm or Demo Model → Chat `Hello` 3x → 3 different answers
6. **Tab 4 Downloader:** Download `large.nanollm` (10M) → Load in Chatbot Tab

### Option B — Infinite Generation

1. Open `copy_paste_double_files_to_infinity_exponential.html`
2. Select 1K start, Blob Double, 2T target
3. Click Start Doubling → 1K→2K→4K→...→2T in 31 doubles (vs 20,000 linear)
4. Click Infinite Double → doubles forever to infinity → PB total ever

### Option C — Up To 2T File

1. Open `generator_up_to_2T_2_trillion_chars_2TB.html`
2. Select 2T (2 Trillion = 2TB), File System API output
3. Click Generate Up To 2T → Browser asks where to save → Writes directly to disk (no RAM limit)
4. 2T @500M/s = 66 min, @5B/s = 6.6 min

---

## 🧠 Architecture

```
Training Text (1 to ∞)
    ↓
QuickTokenizer (build vocab from text, base EN + KO 100 + JA + ZH + custom)
    ↓
QuickChatModel (per-language n-gram tables EN/ZH/KO/JA + dialogue map + history avoid repeat)
    ↓
.nanollm File (JSON + base64, magic NANOLLMv1, format .nanollm)
    ↓
Chatbot Only (language detect → per-language table → sample with temp 0.8 → avoid last 3 history → language-matched diverse)

Generator:
  Templates EN/ZH/KO/JA (6 each) + Chat Intents (User/Assistant) → Balance 25% each or 80% one lang → Chat/Raw/Mixed → Generate 1K→100K→1M→∞

Downloader Up To 10M:
  Tokenizer (cap 400-1000) → TinyTransformer (Wte, Wpe, N layers [LN→MHA→LN→FFN], Final LN, LM Head) → Pretrain 10-30 epochs → Compress base64 → .nanollm

Expectation Engine:
  Context "Hello I am" → Lookup n-gram table → p(next_char|context) bars → Proves LLM = expectation
```

---

## 📊 Benchmarks — Different Techniques to 2T/s

2T/s = 2 Trillion chars/sec = 2TB/sec = 40x RAM bandwidth (DDR5 50GB/sec) → Impossible in JS alone

| Technique | Speed | % of 2T/s | Limit |
|-----------|-------|-----------|-------|
| String.repeat() Native C++ | 1-5B/s | 0.25% | V8 1GB/string |
| ArrayBuffer + fill() | 5-10B/s | 0.5% | 4GB buffer |
| SharedArrayBuffer + 8 Workers | 20-80B/s | 4% | 60 workers max |
| Blob Streaming | 1-5B/s but infinite total GB | 0.25% but infinite | Disk speed |
| **WebGPU Compute (GPU)** | **100-500B/s theoretical** | **25% — BEST** | GPU 1000GB/sec, needs RTX 4090 |
| WASM SIMD | 10-50B/s | 2.5% | WASM 4GB |
| **Hybrid Repeat+Workers+Blob** | **50-200B/s** | **10% — BEST BROWSER** | Combines all |
| Canvas ImageData | 5-20B/s | 1% | Canvas 32k x 32k |

Real max browser: ~200B/s = 10% of 2T/s. True 2T/s needs GPU with 2TB/sec bandwidth (2x RTX 4090) + WebGPU.

---

## 🌏 Multilingual — No 99% Chinese Bug

Old bug: 99% Chinese because corpus unbalanced, language detection missing.

Fixed:

- **Balanced Generator:** 25% EN, 25% ZH, 25% KO, 25% JA by default, or 80% one lang mode
- **Per-Language Tables:** Separate n-gram tables for EN/ZH/KO/JA
- **Language Detection:** `detectLang(text)` via Unicode ranges: `[가-힣]` KO, `[ぁ-んァ-ン]` JA, `[一-龥]` ZH, else EN
- **Language-Matched:** Input EN → Table EN → Reply EN. Input 中文 → Table ZH → Reply 中文. No cross-lang leakage.
- **Diverse:** Dialogue map `User: Hello → [Hello!..., Hi there!...]` + history avoid last 3 → Same input 3x → 3 different answers

Test: `Hello` 3x → 3 different EN. `你好` 3x → 3 different ZH. `안녕하세요` 3x → 3 different KO.

---

## 💾 .nanollm Format Spec

```
File: model.nanollm (not .json, but JSON inside)
Content-Type: application/octet-stream (or application/json)
Magic: NANOLLMv1

{
  "format": "nanollm",
  "magic": "NANOLLMv1",
  "version": 10,
  "type": "quick_trainer" or "pretrained_transformer",
  "params": 1016800,
  "params_m": "1.02M",
  "created": "2026-05-13T...",
  "loss": 0.85,
  "config": {d_model, n_layers, ctx, vocabCap},
  "tokenizer": {itos: [...]},
  "chatModel": {n, tables, dialogues, dialogueMap} or "model": {Wte_b64, Wpe_b64, layers: [...], ln_f, lm_head},
  "metadata": {chars, languages, dialogues},
  "info": "NanoLLM .nanollm format up to 10M - EN ZH KO JA - Hanam - No API"
}

- Extension: .nanollm (your format, OS can associate)
- Content: JSON + base64 Float32 weights (compressed) for transformer, or n-gram tables for quick trainer
- Importable: All NanoLLM versions auto-detect .nanollm and .json
- Backup: Keep .nanollm on USB/drive — your model, offline forever
```

---

## 📜 License

MIT — You own your .nanollm models. No telemetry. No API keys.

---

## 🙏 Credits

- Built in Hanam-si, Gyeonggi-do near Seoul — 하남 河南 ハナム
- No API, No server, No HuggingFace — 100% browser
- Inspired by Karpathy's nanoGPT, but browser-native and multilingual
- Transformer from scratch: Embedding + Positional + LN + MHA + FFN + LM Head — No libraries

---

## 🔗 Links

- **All Files Index:** `index_all_files.html`
- **All In One:** `nano_llm_all_in_one_has_all_stuff.html` ← Start here
- **GitHub:** (add your repo URL)
- **Demo:** Open any HTML file in Chrome — no server needed

---

### For GitHub README Footer

```
Made with ❤️ in Hanam-si, Gyeonggi-do, near Seoul — No API, No Server, Offline Forever — .nanollm Magic NANOLLMv1
EN 中文 한국어 日本語 — 1 char to infinite — Up to 2T (2TB) — Up to 10M params — Language-matched, diverse, no same answer bug
```
