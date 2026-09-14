# LiteLLM Setup Script Guide

An interactive, single-file guide for deploying a local AI stack with [LiteLLM](https://github.com/BerriAI/litellm) as a routing proxy, [Open WebUI](https://github.com/open-webui/open-webui) as the chat frontend, and free-tier API providers (Groq, OpenRouter, Gemini, and others) as the model backends. Includes a config/`​.env` builder, a cheat sheet of 14 free model providers, and a copy-paste Python GUI script (`ai_stack_gui.py`) that automates venv setup, proxy start/stop, and the Docker container for Open WebUI.

**Live guide:** https://solopass.github.io/LiteLLM-Setup-Script-Guide/ *(once GitHub Pages is enabled — see below)*

## What's here

- `index.html` — the whole guide. No build step, no dependencies to install; it pulls Tailwind and Feather Icons from a CDN at load time.

## Hosting on GitHub Pages

1. Push `index.html` to the `main` branch (root of the repo).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save. GitHub will publish it at `solopass.github.io/LiteLLM-Setup-Script-Guide` within a minute or two.

## Notes

- Everything runs client-side; no server, no secrets baked in. The `.env` builder just generates a template — you paste your own API keys locally.

---

## License

**Source-available, noncommercial.** Copyright © 2026 Solopass. Licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE.md).

- ✅ **Free** for personal use, hobby projects, study and research, and for nonprofits, schools and public institutions.
- 💼 **Commercial use** (in a business, product or paid service, or for-profit internal use) needs a paid license. See [COMMERCIAL.md](COMMERCIAL.md), or contact [realsolopass@gmail.com](mailto:realsolopass@gmail.com) · <https://polymatica.pages.dev>.
