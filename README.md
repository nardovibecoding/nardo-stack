# nardo-stack

The open-source tools, projects, and builders that power everything I build. These are the shoulders I'm standing on — full credit to the original makers.

---

## Browser Automation

- **[daijro/camoufox](https://github.com/daijro/camoufox)** — Firefox fork with C++ fingerprint spoofing. Running as a VPS service behind an SSH tunnel for anti-detection browsing on X/Twitter and bot-blocked sites.
- **[Kaliiiiiiiiii-Vinyzu/patchright-python](https://github.com/Kaliiiiiiiiii-Vinyzu/patchright-python)** — undetected Playwright fork. Powers the Xiaohongshu and Douyin MCP servers for headless browser automation.

## Claude Code

- **[headroom-ai/headroom](https://github.com/headroom-ai/headroom)** — local context compression proxy. Routes through `ANTHROPIC_BASE_URL` to reduce token burn on long sessions.
- **[rtk-ai/rtk](https://github.com/rtk-ai/rtk)** — CLI token compression tool. Packs codebases into LLM-ready context with minimal token waste.
- **[obra/superpowers](https://github.com/obra/superpowers)** — Claude Code skills reference. Inspiration for skills architecture and hook patterns.
- **[muratcankoylan/agent-skills-for-context-engineering](https://github.com/muratcankoylan/agent-skills-for-context-engineering)** — skills and context engineering patterns. Reference for building the skill loader and memory system.

## Web Scraping & Social Media

- **[mendableai/firecrawl](https://github.com/mendableai/firecrawl)** — LLM-ready web scraping API. Used as the fallback in the scraping chain (XCrawl primary → Firecrawl → WebFetch).
- **[xcrawl.com](https://xcrawl.com)** — Chinese-built web scraping API with 28-engine SERP support. Primary scraper for content pipelines, cheaper than Firecrawl at scale.
- **[d60/twikit](https://github.com/d60/twikit)** — X/Twitter client without API key. Powers the X curation and feed pipelines.
- **[NanmiCoder/MediaCrawler](https://github.com/NanmiCoder/MediaCrawler)** — Chinese social media scraper for Xiaohongshu, Douyin, Bilibili, Weibo. Reference and fallback for content pipelines.
- **[huccihuang/bilibili-mcp-server](https://github.com/huccihuang/bilibili-mcp-server)** — Bilibili MCP server for video and content access.

## RSS & Feeds

- **[DIYgod/RSSHub](https://github.com/DIYgod/RSSHub)** — everything-to-RSS bridge. Running as a Docker service on VPS for Chinese podcast and platform feeds (小宇宙, Bilibili).

## Voice & Audio

- **[SYSTRAN/faster-whisper](https://github.com/SYSTRAN/faster-whisper)** — CTranslate2 reimplementation of Whisper. Running `large-v3` for voice input to bots.
- **[jaredks/rumps](https://github.com/jaredks/rumps)** — macOS menu bar app toolkit. Powers the voice recording indicator in the status bar.
- **[RVC-Boss/GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)** — zero-shot and fine-tuned voice cloning. Used for persona voice experiments.
- **[FunAudioLLM/CosyVoice](https://github.com/FunAudioLLM/CosyVoice)** — Alibaba's voice cloning model. Tested for Chinese voice synthesis.

## Face Analysis & 3D

- **[google/mediapipe](https://github.com/google/mediapipe)** — Face Mesh model with 468 landmarks, running in-browser. The scanning backbone of the 爱颜 face analysis app.
- **[mrdoob/three.js](https://github.com/mrdoob/three.js)** — 3D face wireframe and overlay rendering. Heat maps, proportion lines, and interactive face rotation all run on this.
- **[pichiliani/ModelsOBJ](https://github.com/pichiliani/ModelsOBJ)** — generic 3D head `.obj` used as a backup mesh in the face app.
- **[cleardusk/3DDFA_V2](https://github.com/cleardusk/3DDFA_V2)** — 3D face reconstruction with dense alignment. Used for side-profile analysis on RunPod.

## Knowledge Graphs

- **[safishamsi/graphify](https://github.com/safishamsi/graphify)** — turn any folder of code, docs, or papers into a navigable knowledge graph with community detection. Powers the `/graphify` skill.

## Media & Video

- **[yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp)** — YouTube and video downloading. Feeds the podcast and video digest pipelines.
- **[FFmpeg/FFmpeg](https://github.com/FFmpeg/FFmpeg)** — audio/video processing backbone. Transcoding, splitting, and format conversion across all media pipelines.
- **[charmbracelet/vhs](https://github.com/charmbracelet/vhs)** — terminal recording to GIF/MP4. Used for demo videos and GitHub README recordings.

## Image Generation

- **[comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)** — node-based Stable Diffusion UI. Used for image generation workflows.

## Code & Security

- **[ast-grep/ast-grep](https://github.com/ast-grep/ast-grep)** — structural code search and linting using AST patterns. Used for codebase-wide refactoring and pattern matching.
- **[gitleaks/gitleaks](https://github.com/gitleaks/gitleaks)** — secret scanning in git repos. Runs as a pre-commit hook to catch leaked credentials.
- **[tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)** — open-source OCR engine. Used for text extraction from images and screenshots.
- **[yamadashy/repomix](https://github.com/yamadashy/repomix)** — pack entire codebases into a single LLM-ready file. Used for context preparation and code review.

## TUI & Desktop

- **[Textualize/textual](https://github.com/Textualize/textual)** — Python TUI framework. Used for the TokenGotchi arena terminal UI.

---

Built by [@nardovibecoding](https://github.com/nardovibecoding)
