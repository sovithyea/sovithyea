<div align="center">

# Hi, I'm Vith (Sovithyea Prach)

**Bachelor of Computer Science (Artificial Intelligence) @ Swinburne University of Technology, Melbourne**

I build AI-powered products end to end, from a React Native app with real testers to the ML models and LLM tools behind them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/sovithyea-prach-68037923b)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:prachsovithyea11@gmail.com)

</div>

---

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### 🦝 [HungryRaccoon](https://hungryraccoonapp.com)
**A social food diary for Cambodia: rate where you ate, make lists, follow friends.**

React Native app (iOS and Android from one codebase) on Supabase, with a Next.js reference web app and a shared TypeScript core. Postgres row-level security instead of a custom server. Around 6,150 places in the dev catalogue across six launch cities. v2 of my earlier [FoodRaccoon](https://foodraccoon.vercel.app).

`React Native` `Expo` `TypeScript` `Supabase` `Postgres` `Next.js` `Drizzle` `Vitest`

**Status:** iOS test builds on TestFlight, not yet in the App Store. Team of five; I've written all 417 commits.

[Website](https://hungryraccoonapp.com) · Code private

</td>
<td width="50%" valign="top">

### 🧱 Athena · Rocket Academy internship
**A chat companion for kids aged 7 to 12 building with LEGO Education SPIKE.**

A student uploads their `.llsp3` project and Athena reads the actual program by parsing the file directly (no screenshots, no OCR), then helps in words a nine-year-old can use. Two guarantees are enforced in code, not in prompts: it never names a block that isn't in a verified catalogue, and its replies are scored for reading level.

`TypeScript` `Node.js` `Claude API` `node:test`

**Status:** in development since August 2026.

Code private (Rocket Academy)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎵 [SongRaccoon](https://songraccoon.vercel.app)
**Describe a feeling, get a playlist.**

Claude reads a plain-language mood and picks songs, then Spotify search matches each pick to a real track. Mainstream or niche mode, saved search history, and a "taste" report built from your Spotify top artists and tracks. Rate-limited Claude routes.

`Next.js 14` `TypeScript` `Claude API` `Spotify Web API` `Supabase` `Upstash Redis` `Tailwind CSS`

[Live](https://songraccoon.vercel.app) · [Code](https://github.com/sovithyea/songraccoon)

</td>
<td width="50%" valign="top">

### ✨ [Prompt Polish](https://github.com/sovithyea/prompt-engineer-ai-agent)
**One click turns a rough prompt into a well-structured one, right inside claude.ai, ChatGPT and Gemini.**

Manifest V3 browser extension. It asks up to two clarifying questions if the prompt is vague, then rewrites it in place. The Anthropic key lives in a Cloudflare Worker, never in the extension bundle.

`TypeScript` `Chrome Extension (MV3)` `Cloudflare Workers` `Claude API` `esbuild`

**Status:** v1.0.0. The API has no rate limiting yet (a deliberate, documented choice).

[Code](https://github.com/sovithyea/prompt-engineer-ai-agent)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ⚽ World Cup 2026 predictors
**Two ML pipelines for the 2026 World Cup.**

[Tournament winner](https://github.com/sovithyea/2026_worldcup_prediction): ELO ratings and XGBoost, then 10,000 Monte Carlo simulations of the tournament. Reports ~57% accuracy in time-series cross-validation, against a ~48.5% always-home-win baseline.
[Round-of-32 matches](https://github.com/sovithyea/wc26_ro32_predictor): a calibrated XGBoost win/draw/loss classifier blended 60/40 with a Dixon-Coles Poisson model for scorelines, with a Streamlit app.

`Python` `XGBoost` `scikit-learn` `SciPy` `pandas` `Streamlit` `Plotly`

**Status:** the round-of-32 model has no backtest yet.

</td>
<td width="50%" valign="top">

### 🏎️ [2026 F1 Race Predictor](https://github.com/sovithyea/2026_f1_prediction)
**Predicting finishing positions round by round, on real 2026 FastF1 data.**

A gradient boosting regressor retrains on every completed round using qualifying gaps, practice-session deltas and team scores. Predictions are checked against actual results with `tracker.py`.

`Python` `scikit-learn` `FastF1` `pandas` `Matplotlib`

**Status:** 6 rounds predicted and tracked (Australia to Monaco); paused since June.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎙️ HungryRaccoon Meeting Notes
**A private meeting recorder: record or upload, get a summary, decisions, action items and next agenda.**

Transcription and speaker separation run locally on the Mac. Only the transcript text goes to Claude to write the notes. Optional 20-second voice samples let it name speakers automatically.

`Python` `FastAPI` `MLX Whisper` `sherpa-onnx` `Claude`

**Status:** internal tool for the HungryRaccoon team.

Code private

</td>
<td width="50%" valign="top">

### 🏛️ [Politidle](https://hellscabinet-glny.vercel.app)
**A satirical alternate-history game: build a cabinet from random historical figures, then watch it handle a crisis.**

Five roles, six fresh candidates a round, daily and free-play seeds, and a narrated outcome written by Claude. 122 figures and 20 historical events.

`TypeScript` `React` `Vite` `Claude API` `Zod` `Vercel`

[Play](https://hellscabinet-glny.vercel.app) · Code private

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br>

| Project | What it is | Stack |
|---|---|---|
| [Hermes](https://github.com/sovithyea/hermes) | Turns a book (EPUB, PDF, TXT, page photos) into a full-cast audiobook with local AI: a local LLM attributes each line to a speaker, Kokoro-82M voices it | Python, Ollama, Kokoro, FastAPI |
| [MapRaccoon](https://mapraccoon.vercel.app) | Going-out planner for friends in Phnom Penh | Next.js, TypeScript, Mapbox, Zustand, Vitest |
| [FoodRaccoon](https://foodraccoon.vercel.app) | Restaurant discovery for Phnom Penh, v1 of HungryRaccoon | Next.js, Supabase, Mapbox, Tailwind |
| [Traffic flow prediction](https://github.com/sovithyea/cos30019_assignment2_b) | LSTM, GRU and other models forecasting traffic at 40 Melbourne intersections (coursework) | TensorFlow, scikit-learn |
| [coc-advisor](https://github.com/sovithyea/coc_bot) | Discord bot with team comps, counters and tier lists for Clash of Critters | discord.js, SQLite, Claude API |
| [SCSA website](https://github.com/sovithyea/scsa_website) | Website for the Swinburne Cambodian Student Association | React, Material UI |
| [Roguelike](https://github.com/sovithyea/rougelike_project) | ASCII dungeon crawler, ported from the Rust tutorial to Go | Go, tcell |
| [Instagram Stats Tracker](https://github.com/sovithyea/instagram_stats_tracker) | Client-side dashboard for your Instagram data export: followers, unfollowers, history | JavaScript |

</details>

---

## Tech stack

| | |
|---|---|
| **Languages** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white) ![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4169E1?logo=postgresql&logoColor=white) |
| **AI / LLM** | ![Claude API](https://img.shields.io/badge/Claude_API-D97757?logo=anthropic&logoColor=white) ![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white) ![Whisper](https://img.shields.io/badge/Whisper_(MLX)-412991?logoColor=white) |
| **ML & data** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white) |
| **Mobile & web** | ![React Native](https://img.shields.io/badge/React_Native-20232A?logo=react&logoColor=61DAFB) ![Expo](https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?logo=fastapi&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-000000?logo=threedotjs&logoColor=white) |
| **Data & infra** | ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) |

---

## GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sovithyea&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats" height="165"/>
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sovithyea&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&hide=jupyter%20notebook" alt="Top languages" height="165"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=sovithyea&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=sovithyea&color=6366f1&style=flat-square&label=profile+views" alt="Profile views"/>
</p>
