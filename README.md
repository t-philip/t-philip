# Hi, I'm T. Philip 👋

An explorer in the world of technology — I build and self-host things across **AI,
Python, homelab infrastructure, networking and automation**.

Most of what you'll find here started as something I wanted for myself, then got
cleaned up enough to be worth sharing. Everything is self-hostable, documented, and
free to use.

---

## 📂 Projects by category

### 📡 ESP32 Projects

| Project | What it does |
|---|---|
| **[spotify-nowplaying](https://github.com/t-philip/spotify-nowplaying)** | A WiFi display showing your currently-playing Spotify track — album art, progress, and transport controls from a web dashboard. Observes playback on your *other* devices, so no audio hardware is needed. |
| **[wifi-signal-scanner](https://github.com/t-philip/wifi-signal-scanner)** | A live WiFi signal-strength meter on a small TFT — strength label, RSSI in dBm, and a scrolling history graph for walking a signal around a building. You pick the network in a browser, so nothing needs recompiling. |

### 🛡️ Blocklists for DNS

| Project | What it does |
|---|---|
| **[blocklists](https://github.com/t-philip/blocklists)** | Hosts-format blocklists for Pi-hole, AdGuard Home, or any hosts-file blocker. Malware/phishing domains and streaming-service domains, with setup instructions for both. |

Drop straight into your blocker:
- [`malware_domains`](https://raw.githubusercontent.com/t-philip/blocklists/main/hosts/malware_domains)
- [`online_streaming_domains`](https://raw.githubusercontent.com/t-philip/blocklists/main/hosts/online_streaming_domains)

### 🔐 Tools

| Project | What it does |
|---|---|
| **[bitwarden-vaultwarden-sync](https://github.com/t-philip/bitwarden-vaultwarden-sync)** | Syncs a Bitwarden.com vault to a self-hosted Vaultwarden instance — attachments included — with encrypted backups and Telegram alerts. |

### 🐍 Python

| Project | What it does |
|---|---|
| **[sky-radar](https://github.com/t-philip/sky-radar)** | Real-time flight tracking dashboard — Flask + Socket.IO backend, Leaflet map, OpenSky Network API, with watchlist alerting and JSONL logging. |
| **[omnimeter](https://github.com/t-philip/omnimeter)** | Self-hosted dashboard for household power, gas, water and battery usage. Works with any P1 smart meter — live polling or CSV import — tracks costs against your own energy tariff, and estimates solar self-sufficiency. |

### 🖥️ Scripts & Guides

| Project | What it does |
|---|---|
| **[scripts](https://github.com/t-philip/scripts)** | Router outage monitoring (systemd + CSV logging), Windows app provisioning via `winget`, an EVE-NG on VMware setup guide, and Python utilities. |

---

## 🛠️ What to expect

These started as tools I wanted for myself, so they're shaped by having to live
with them rather than demo them. They run on your own hardware — no account to
create, no hosted service in the middle, no telemetry.

Every project here carries a tagged release with notes written for someone
running the software rather than reading commit history, and its own issue
tracker with templates. Where something is implemented but not yet verified, the
documentation says so rather than implying otherwise.

Every project also ships a design spec (`docs/DESIGN_SPEC.md`) explaining how it's
built and why, reconciled against the actual shipped code — not a pre-launch plan
left to go stale.

## 🐞 Found a bug? Have an idea?

Every project above has its own issue tracker. Open the repository you're using
and file an issue there — each one has templates so you know what's useful to
include. Bug reports, documentation corrections and feature ideas are all welcome.

For anything **security-related** in
[bitwarden-vaultwarden-sync](https://github.com/t-philip/bitwarden-vaultwarden-sync),
please use its [private reporting channel](https://github.com/t-philip/bitwarden-vaultwarden-sync/security/advisories/new)
rather than a public issue.

---

<sub>All public content is open to use — please credit **t-philip**. Repositories are
GPL-3.0 licensed unless stated otherwise.</sub>
