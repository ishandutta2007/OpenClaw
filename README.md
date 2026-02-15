# OpenClaw: Open-Source Autonomous Personal AI Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)](https://github.com/openclaw/openclaw/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/openclaw/openclaw?style=social)](https://github.com/openclaw/openclaw/network/members)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

🦞 **OpenClaw** — The AI that actually *does things* for you.  
Your private, self-hosted, autonomous personal AI assistant that lives in your messaging apps (WhatsApp, Telegram, Discord, Slack, iMessage, Signal & more), remembers everything, acts proactively, and executes real tasks on your behalf.

From clearing your inbox and scheduling meetings to checking you in for flights, summarizing documents, running terminal commands, controlling smart devices, pushing code, or even building new skills autonomously — OpenClaw turns natural language into real-world action.

Fully **open-source**, privacy-first, runs locally on your hardware (Mac, Linux, Windows, Raspberry Pi, VPS), bring-your-own-LLM (Claude, GPT, local models & more). No subscriptions, no cloud lock-in.

Perfect if you're searching for:  
**open source personal AI assistant**, **autonomous AI agent open source**, **self-hosted AI assistant**, **local AI agent 2026**, **proactive personal AI**, **OpenClaw GitHub**, **Moltbot successor**, **Clawdbot open source**

## Table of Contents

- [Why OpenClaw?](#why-openclaw)
- [Key Features](#key-features)
- [How It Works](#how-it-works)
- [Getting Started](#getting-started)
- [Supported Platforms & Integrations](#supported-platforms--integrations)
- [Security & Privacy](#security--privacy)
- [Community & Skills](#community--skills)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Why OpenClaw?

Most AI chatbots just talk.  
**OpenClaw acts.**  

Born in late 2025 (originally as Clawdbot → Moltbot → now OpenClaw), it exploded to become one of the fastest-growing open-source projects ever — crossing massive GitHub stars in days thanks to its agentic power, persistent memory, and ability to feel like a real digital employee.

- Runs **locally** → full data ownership & privacy  
- **Proactive** heartbeat — it can message you first when something important happens  
- **Self-improving** — autonomously writes code to create new tools/skills  
- Integrates deeply with your life via messaging apps & computer access  
- Community-driven — thousands of developers building skills & extensions

> "OpenClaw is the closest thing to JARVIS we've seen in open source." — Community member

## Key Features

- 🎯 **Autonomous Task Execution** — send emails, manage calendar, book flights, research, automate workflows  
- 🧠 **Persistent Long-Term Memory** — remembers preferences, context, history across all sessions  
- 💬 **Multi-Channel Access** — chat via WhatsApp, Telegram, Discord, Slack, iMessage, Signal & more  
- 🔧 **Tool & Skill System** — extensible via plugins/skills (email, files, browser, terminal, smart home…)  
- ⚡ **Proactive Behavior** — heartbeat system notifies you of important events automatically  
- 🛡️ **Self-Hosted & Private** — runs on your machine, no data leaves unless you allow it  
- 🤖 **Bring Your Own Model** — Claude, GPT, Gemini, Llama, Mistral, local LLMs…  
- 🔄 **Self-Extending** — can write & install new code/skills to solve novel problems  

## How It Works

1. **Gateway** — local control plane routes messages, manages sessions & memory  
2. **LLM Brain** — powerful model (e.g. Claude Opus/Sonnet) reasons & plans  
3. **Tools & Skills** — execute actions (read/write files, send messages, run commands…)  
4. **Channels** — talk to your assistant from any supported messaging app  
5. **Heartbeat** — periodic proactive checks & notifications  

Your assistant lives 24/7 on your hardware, always ready, always remembering.

## Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/openclaw/openclaw.git
cd openclaw

# 2. Follow the quickstart (Docker recommended for easiest setup)
docker compose up -d

# 3. Open the Control UI
# http://localhost:18789 (or your-ip:18789) — add your LLM API key

# 4. Connect a messaging channel (WhatsApp/Telegram/etc.)
# Follow in-app instructions

# Full docs: https://docs.openclaw.ai
```

Detailed guides: [Quick Start](https://docs.openclaw.ai/getting-started) | [Docker](https://docs.openclaw.ai/install/docker) | [Mac M4](https://docs.openclaw.ai/install/mac) | [Security Best Practices](https://docs.openclaw.ai/security)

## Supported Platforms & Integrations

- **OS**: macOS, Linux, Windows, Raspberry Pi, VPS  
- **Messaging**: WhatsApp, Telegram, Discord, Slack, iMessage, Signal, SMS (via bridges)  
- **LLMs**: Anthropic Claude, OpenAI GPT, Google Gemini, local models (Ollama, LM Studio…)  
- **Tools**: Email (Gmail/Outlook), Calendar, Files, Terminal, Browser, Smart Home, Todoist, Notion, Spotify, Hue…  
- **Extensibility**: Molthub / OpenClaw Skills Registry for community plugins

## Security & Privacy

OpenClaw gives powerful system access — treat it with care.

- Runs locally — your data stays yours  
- Granular permissions per skill/tool  
- Audit logs of all actions  
- Sandboxing options available  
- **Warning**: Only grant access you trust. Review community security guides.

See: [Security Model](https://docs.openclaw.ai/security/model) | [Best Practices](https://docs.openclaw.ai/security/best-practices)

## Community & Skills

Join thousands building the future of personal AI agents:

- 🌐 Website: https://openclaw.ai  
- 📖 Docs: https://docs.openclaw.ai  
- 💬 Discord / Community: Check openclaw.ai  
- 🔍 Skills Registry: https://clawdhub.com (or molthub)  
- Awesome List: https://github.com/VoltAgent/awesome-openclaw-skills  

Star ⭐ the repo if you're excited about autonomous open-source AI!

## Contributing

We welcome contributions — code, skills, docs, bug reports, ideas.

1. Fork & branch  
2. Make changes  
3. Open PR with clear description  

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License — see [LICENSE](LICENSE)

Individual dependencies & skills may have their own licenses.

## Acknowledgments

- Creator: Peter Steinberger (@steipete)  
- Inspired by early experiments → Clawdbot → Moltbot → OpenClaw  
- Huge thanks to the explosive community that made this one of the fastest-growing open-source AI projects ever  

🦞 Let's build the future of personal AI — together!

**SEO keywords**: open source autonomous personal AI assistant, OpenClaw GitHub, self-hosted AI agent, proactive local AI assistant, open source Claude agent, autonomous AI 2026, privacy-first personal AI, Moltbot open source, Clawdbot successor
s