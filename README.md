# nardo-stack

The open-source tools, projects, and builders that power everything I build. These are the shoulders I'm standing on — full credit to the original makers.

---

## Browser Automation

- **[camoufox/camoufox](https://github.com/daijro/camoufox)** — Firefox fork with C++ fingerprint spoofing. Running as a VPS service behind an SSH tunnel for anti-detection browsing on X/Twitter and bot-blocked sites.

## Claude Code

- **[headroom-ai/headroom](https://github.com/headroom-ai/headroom)** — local context compression proxy. Routes through `ANTHROPIC_BASE_URL` to reduce token burn on long sessions.

## Web Scraping

- **[mendableai/firecrawl](https://github.com/mendableai/firecrawl)** — LLM-ready web scraping API. Used as the fallback in the scraping chain (XCrawl primary → Firecrawl → WebFetch).
- **[xcrawl.com](https://xcrawl.com)** — Chinese-built web scraping API with 28-engine SERP support. Primary scraper for content pipelines, cheaper than Firecrawl at scale.

## RSS & Feeds

- **[DIYgod/RSSHub](https://github.com/DIYgod/RSSHub)** — everything-to-RSS bridge. Running as a Docker service on VPS for Chinese podcast and platform feeds (小宇宙, Bilibili).

## Voice

- **[SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)** — CTranslate2 reimplementation of Whisper. Running `large-v3` for voice input to bots.
- **[jaredks/rumps](https://github.com/jaredks/rumps)** — macOS menu bar app toolkit. Powers the voice recording indicator in the status bar.

## Face Analysis & 3D

- **[google/mediapipe](https://github.com/google/mediapipe)** — Face Mesh model with 468 landmarks, running in-browser. The scanning backbone of the 爱颜 face analysis app.
- **[mrdoob/three.js](https://github.com/mrdoob/three.js)** — 3D face wireframe and overlay rendering. Heat maps, proportion lines, and interactive face rotation all run on this.
- **[pichiliani/ModelsOBJ](https://github.com/pichiliani/ModelsOBJ)** — generic 3D head `.obj` used as a backup mesh in the face app.
- **[Textualize/textual](https://github.com/Textualize/textual)** — Python TUI framework. Used for the TokenGotchi arena terminal UI.

---

Built by [@nardovibecoding](https://github.com/nardovibecoding)
