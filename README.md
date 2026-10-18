# Hi, I'm Daniil Karpenko 👋

I build smart-home systems, local AI tools, and practical automations, both at Syncopia and for my own projects.

My work spans Home Assistant integrations, Telegram bots, web scraping, monitoring, and API proxying. I also developed **Богатырь (Bogatyr)**, a bot for VK.

[Personal Telegram](https://t.me/techno_boggart) · [Syncopia Telegram](https://t.me/syncopia_ge) · [Syncopia YouTube](https://www.youtube.com/@syncopia_ge)

**Discord:** Donkarization

## Featured projects

### [Inference Broker](https://github.com/dankarization/ollama-inference-broker)
A local queue and scheduler for a shared GPU executor, currently focused on Ollama workloads. Includes durable jobs, model-aware scheduling, Wake-on-LAN, and an operational dashboard.

**Planned:** GPU speech recognition with Whisper and GigaAM, equal scheduling weights (1) alongside other models, and a 20-minute model unload timeout.

### [OpenClaw Telegram Bot API Proxy](https://github.com/dankarization/openclaw-telegram-bot-api-proxy)
A local-first bridge between OpenClaw and the Telegram Bot API. Handles large files, coordinates polling, and applies explicit rules for cloud fallback.

### [AI Usage Dashboard](https://github.com/dankarization/ai-usage-dashboard-local)
A self-hosted HTML web dashboard for AI usage, provider quotas, model breakdowns, and estimated costs. Built on [grapeot/ai_usage_dashboard](https://github.com/grapeot/ai_usage_dashboard), with a FastAPI web UI and additional integrations.

## Smaller tools

- [QNAP Plex Watchdog](https://github.com/dankarization/qnap-plex-watchdog) — health checks and guarded recovery for a QNAP Plex QPKG installation.
- [ASG Lift Code Fetcher](https://github.com/dankarization/asg-code-fetcher) — Telegram bot for daily lift-code notifications and on-demand access.

## Open-source contributions

Alongside my own projects, I contribute fixes and device support upstream:

- [Home Assistant](https://github.com/home-assistant/core/pull/170563) — tilt controls for Overkiz UpDownSheerScreen.
- [Zigbee2MQTT](https://github.com/Koenkk/zigbee-herdsman-converters/pull/12193) — support for a Tuya four-gang switch.
- [OpenClaw](https://github.com/openclaw/openclaw/pull/94118) — a fix for Telegram rich local Markdown links.
- [SmartIR](https://github.com/smartHomeHub/SmartIR/pull/1556) — submitted improvements to IR remote codes and fan controls, including EGLO fans and Tadiran climate devices. Pull requests are open.
