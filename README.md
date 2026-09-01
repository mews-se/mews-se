# Hej! 👋

I'm Martin, a Linux tinkerer from Stockholm, Sweden. Small Bash tools for Debian, often involving Dell hardware that refuses to cool itself — plus a self-hosted bookkeeping app, a maintained Docker image or two, the occasional PowerShell fix for a Windows annoyance, and lately a pair of iPhone apps written in SwiftUI.

## 🔧 What I build

**Self-hosting**
- [firmabok](https://github.com/mews-se/firmabok): Swedish bookkeeping for sole traders (enskild firma), self-hosted on your own network without cloud dependencies
- [docker-observium](https://github.com/mews-se/docker-observium): unofficial Docker image for Observium CE — rebuilt weekly for amd64/arm64, mirrored to [Docker Hub](https://hub.docker.com/r/mewsse/observium)
- [observium-ce-archive](https://github.com/mews-se/observium-ce-archive): keeps every Observium CE build around, since upstream only ever publishes the latest one
- [dietpi-factory](https://github.com/mews-se/dietpi-factory): deploy preconfigured headless [DietPi](https://github.com/MichaIng/DietPi) from one wizard profile

**Tesla**
- [EVLog](https://github.com/mews-se/evlog-ios): native iPhone client for your own [TeslaMate](https://github.com/teslamate-org/teslamate) server — drives with route maps, charge curves, statistics and battery health, reading only from machines you run yourself
- [WallConnectorLog](https://github.com/mews-se/wallconnectorlog): self-hosted logger for the Tesla Wall Connector Gen 3 — the charger keeps no history, so this polls its local API around the clock and derives real charge sessions, with a Grafana dashboard included
- [WallConnectorLog for iOS](https://github.com/mews-se/wallconnectorlog-ios): the iPhone companion to that server — live charger status, the sessions it has derived and the charger's lifetime counters, with a demo mode a typed word away
- [teslamate-maintenance](https://github.com/mews-se/teslamate-maintenance): the maintenance chapter of the TeslaMate docs as one interactive menu — verified backups, guarded restores, closing or deleting drives and charges, PostgreSQL major upgrades

**Keeping Dell machines cool on Linux**
- [dellfan](https://github.com/mews-se/dellfan): fan control for Dell OptiPlex desktops — detects what the machine supports and sets it up
- [dell-bios-fan-control](https://github.com/mews-se/dell-bios-fan-control): toggle SMBIOS automatic fan control on Dell machines

**Debian host tooling**
- [hostctl](https://github.com/mews-se/hostctl): one command to update, inspect and manage your hosts
- [geodebtest](https://github.com/mews-se/geodebtest): autodetects your location and benchmarks your country's Debian mirrors
- [update-fastfetch](https://github.com/mews-se/update-fastfetch): keep [fastfetch](https://github.com/fastfetch-cli/fastfetch) up to date on Debian without waiting for the repos

**Windows**
- [no-new-outlook](https://github.com/mews-se/no-new-outlook): removes new Outlook and keeps it from coming back
- [TPFanCtrl2](https://github.com/mews-se/TPFanCtrl2): fan control for ThinkPads, carrying on the archived TPFanCtrl2 line

## 📈 Stats

![Followers](https://img.shields.io/github/followers/mews-se?logo=github&label=followers)
![Stars](https://img.shields.io/github/stars/mews-se?affiliations=OWNER&logo=github&label=stars)

![Metrics](github-metrics.svg)

---

💚 Proud sponsor of open-source projects I rely on.
