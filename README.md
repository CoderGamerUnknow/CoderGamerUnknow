# Hi, I'm CoderGamerUnknow 👋

I build things that run **on your own machine** — offline-first web apps, local AI
tooling, and bots that don't need a subscription. Most of my projects share one rule:
if it can work without a server, it should.

**Usually working in:** TypeScript · Python · React · Node · FastAPI · SQLite ·
Ollama · browser APIs (Web Audio, Canvas, WASM)

---

### What I've built

| Project | What it is | Stack |
| --- | --- | --- |
| [Project-Tango](https://github.com/CoderGamerUnknow/Project-Tango) | Local-first MCP server for e-commerce data — 8 tools over products, inventory, orders and sales, with durable SQLite state and a DataProvider seam for live Shopify/Stripe | TypeScript, MCP, SQLite |
| [shadow-vox](https://github.com/CoderGamerUnknow/shadow-vox) | Real-time voice-cloning Discord bot — record a voice in VC, speak in it later, with consent gating, VAD and voice→voice mode | Node, discord.js, Python, XTTS-v2 |
| [Whatsapp-helper](https://github.com/CoderGamerUnknow/Whatsapp-helper) | A fully local family assistant on WhatsApp: expense tracking with a validation gate, bill summaries, tech help and recipes | FastAPI, Ollama, faster-whisper, SQLite |
| [File-managing-system](https://github.com/CoderGamerUnknow/File-managing-system) | Event-driven file organiser daemon: watches folders, sorts by rules, optional local-AI fallback, undo journal, loopback dashboard | Python, watchdog |
| [Backround-Remover](https://github.com/CoderGamerUnknow/Backround-Remover) | Three local background removers in one repo: Streamlit batch + ZIP, CustomTkinter folder GUI, and a fully client-side React app with brushes | Python, rembg, React |
| [StormWatch](https://github.com/CoderGamerUnknow/StormWatch) | Zero-backend weather hazard monitor: three global models fused on-device, climate-aware rules, and a watchdog that expires stale alerts instead of lying | HTML, CSS, JS |
| [News-letter](https://github.com/CoderGamerUnknow/News-letter) | *The Daily Ledger* — a print-style newspaper front end streaming live RSS headlines | Next.js App Router, TypeScript |
| [Website-code-aniamtions-and-all-that-shii](https://github.com/CoderGamerUnknow/Website-code-aniamtions-and-all-that-shii) | Animation-heavy NVIDIA GeForce concept site: scroll-scrubbed canvas, magnetic cursor, parametric SVG GPUs, headless-Chrome animation audit in CI | Vite, React, GSAP, Lenis |
| [Retro-Pomodoro-Focus-Timer](https://github.com/CoderGamerUnknow/Retro-Pomodoro-Focus-Timer) | A CRT-arcade Pomodoro timer in one offline-capable HTML file: phosphor theme mixer, procedural ambient audio, XP stats | Vanilla JS, PWA |
| [Life-Skills-Comitties](https://github.com/CoderGamerUnknow/Life-Skills-Comitties) | Committee site with a video library and passcode-gated admin — direct browser-to-Blob uploads, signed sessions | HTML, JS, Vercel Blob |
| [EchoValley](https://github.com/CoderGamerUnknow/EchoValley) | Local-first audio / podcast workspace — record, edit and race short voice memos without leaving your machine | Vanilla JS, Web Audio, PWA |

---

### How I like to build

- **Local-first by default.** `localStorage`, SQLite, or a loopback server beats a
  hosted database for a personal tool.
- **Honest failure.** A stale or offline app should say so, not pretend it's live.
- **No key soup.** Free, key-less APIs first; paid keys optional and gitignored.
- **Cheap to run.** Battery-friendly animation, one dependency where possible, and
  no infrastructure bill for something used by a handful of people.

<sub>Every repository here has a README that explains what it does, how to run it,
and what it deliberately doesn't do.</sub>
