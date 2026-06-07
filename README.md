<div align="center">

<img src="https://raw.githubusercontent.com/DragonF1/aura-releases/main/assets/aura-banner.png" alt="AURA" width="440" />

### Your all-in-one Hypixel proxy for Minecraft 1.8.9

Live stat overlays · auto-scout · threat tags · a native anticheat engine — **20+ tools** in one lightweight launcher.

<p>
  <a href="https://github.com/DragonF1/aura-releases/releases/latest"><img src="https://img.shields.io/github/v/release/DragonF1/aura-releases?label=version&color=2bd4c4&style=for-the-badge" alt="Latest version" /></a>
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" />
  <img src="https://img.shields.io/badge/macOS-Universal-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS" />
  <a href="https://discord.gg/jvPqweaeC2"><img src="https://img.shields.io/badge/Discord-Join-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

**[⬇  Download the latest release](https://github.com/DragonF1/aura-releases/releases/latest)**  ·  **[💬  Join the Discord](https://discord.gg/jvPqweaeC2)**

</div>

---

## What is AURA?

AURA is a **local Minecraft proxy + launcher** that supercharges Hypixel **BedWars** (plus SkyWars, Duels, and lobbies) on **Minecraft 1.8.9**. It sits quietly between your game and Hypixel and adds live overlays, scouting, automation, and a built-in anticheat — **no mods, no client replacement**. Download it, point your game at it, and play.

> Works alongside any 1.8.9 setup — Vanilla, Lunar, Badlion, Feather, and more.

## ⬇ Download &amp; Install

| Platform | Installer | |
|---|---|---|
| **Windows 10 / 11** | `Aura.Launcher_…_x64-setup.exe` | **[Download →](https://github.com/DragonF1/aura-releases/releases/latest)** |
| **macOS** (Apple Silicon + Intel) | `Aura.Launcher_…_universal.dmg` | **[Download →](https://github.com/DragonF1/aura-releases/releases/latest)** |

> 🔄 **Auto-updates are built in** — once installed, AURA keeps itself on the latest version.

<details>
<summary><b>⚠️  "Windows protected your PC" / "AURA can't be opened" — how to open it</b></summary>

<br>

AURA is an indie app and isn't paid-signed by Microsoft/Apple yet, so your OS shows a **one-time** warning. It's safe to allow:

- **Windows (SmartScreen):** click **More info → Run anyway**.
- **macOS (Gatekeeper):** **right-click** the app → **Open** → **Open**. *(Or: System Settings → Privacy &amp; Security → **Open Anyway**.)*

</details>

## 🚀 Getting started

1. **Install &amp; open AURA** (see the note above on first launch).
2. **Sign in with Discord** — unlocks config profiles, syncing, and account linking.
3. **Add your Hypixel API key** in **Settings** — create one at **[developer.hypixel.net](https://developer.hypixel.net)**. The proxy stays locked until a valid key is set.
   <br><sub>Optional: add **Urchin / Seraph / Bordic / Winstreak** keys for threat tags and ping lookups.</sub>
4. **Hit the master switch** on the Dashboard to start the proxy (it listens on `localhost:25570`).
5. **In Minecraft 1.8.9**, add a server with the address **`localhost:25570`** and **join it**. Sign in to Microsoft when prompted *(first time only)*.
6. **You're in.** Overlays, tags, and commands are live — type **`.cmds`** in chat to see everything.

> 💡 **Hands-off start:** in **Settings → Auto start Aura**, pick **On PC start** (launch AURA at login) or **On Minecraft launch** (auto-start the proxy when your game opens).

## ✨ Features

A taste of the **20+** tools built in:

| | |
|---|---|
| 🛡️ **Native Anticheat** | Rust engine flags 14 cheat types — Reach, KillAura, Scaffold, AutoClicker, Velocity &amp; more — with instant alerts. |
| 📊 **Live Stat Overlay** | Prestige titles, FKDR / WLR / BBLR / KDR, ping &amp; health, right in the tab list. |
| 🔎 **Auto-Scout &amp; Party Finder** | Scans lobby chat and `/who`, tracks stats, and auto-invites qualifying players. |
| 🚩 **Threat Tags** | Cross-checks Urchin + Seraph and surfaces the most severe threat with sounds/alerts. |
| 🗺️ **Map Blacklist &amp; Auto-Requeue** | Dodge bad maps (or whitelist favorites) — auto-requeues as party leader. |
| 🤖 **Nick Bot** | Auto-rolls `/nick` for `og` / `any` / `keyword` / `specific` nicks. |
| 😴 **Slumber Tracker** | Tracks Slumber quests + tickets and reminds you before reset. |
| ⏱️ **Generator Timers** | Diamond / Emerald timers in the tab-list header &amp; footer. |
| 🛒 **Shop Protections** | Blocks sword downgrades and duplicate buys in BedWars. |
| 🏆 **Leaderboards** | `.lb` for top-10 BedWars / SkyWars / Duels across daily → lifetime. |
| 🗂️ **Config Profiles** | Save &amp; switch profiles (4 free, 9 when Discord-linked) and export to share. |

<details>
<summary><b>See the full feature list</b></summary>

<br>

- Native Rust **anticheat** engine (14 detections)
- Live **stat overlay** (BedWars / SkyWars / Duels)
- **Auto-scout** &amp; party finder
- **Urchin + Seraph** threat tags
- Map **blacklist / whitelist** + auto-requeue
- **Nick bot** &amp; nick management
- **Slumber** quest + ticket tracker
- **Potion &amp; trap** alerts (Mining Fatigue, expiring effects)
- **Ping lookup** (Winstreak / Bordic)
- **Number denick**
- Custom **emoji** support
- **Generator timers**
- BedWars **shop protections**
- **Microsoft auth** management (`.a logout`)
- In-game **settings GUI** + chat settings
- **Configuration profiles** (export / share)
- **Discord account linking** (up to 5 accounts)
- Stats **leaderboards** (`.lb`)
- **Party manager** automation
- In-game **nametag customization** (ping / threat / flags)

</details>

## ⌨️ Commands

Type **`.cmds`** for the full list and **`.help`** for usage. Highlights:

```
.bw .sw .dl                stats for a player
.compare                   compare two players
.stars .fkdr .wlr .kdr     quick single-stat lookups
.lb                        leaderboards
.daily .weekly .monthly    period stats
.rq                        requeue
.blacklist  .nickbot  .tags  .slumber  .ping  .denick
.a link   .a unlink   .a logout   .a settings
```

## 📦 Requirements

- **Minecraft 1.8.9** (Java Edition) with a Hypixel-ready Microsoft account
- A **Hypixel API key** — required *(free from [developer.hypixel.net](https://developer.hypixel.net))*
- **Windows 10/11** or **macOS 11 (Big Sur)+** — Apple Silicon or Intel
- *Optional:* Urchin / Seraph / Bordic / Winstreak API keys for tags &amp; ping

## 💬 Community &amp; Support

Releases, help, and bug reports all live in the Discord — it's the hub:

<div align="center">

**[➜  Join the AURA Discord](https://discord.gg/jvPqweaeC2)**

</div>

---

<div align="center">
<sub>AURA is an independent tool and is <b>not affiliated with, endorsed by, or associated with Hypixel or Mojang / Microsoft</b>. Use responsibly and at your own risk.</sub>
</div>
