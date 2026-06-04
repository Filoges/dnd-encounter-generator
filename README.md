# 🎲 D&D Random Encounter Generator

A fully offline web app for managing random encounters in Dungeons & Dragons 5e sessions. No installation required — just a single HTML file you open in your browser.

---

## ✨ Features

### 🎲 Roll Dice
- **Encounter check roll** with a configurable die (d4–d20)
- **Encounter generation** using a 2d8 bell curve distribution — central encounters appear more frequently
- **Automatic stat block**: when an encounter triggers, the app searches [Open5e](https://open5e.com/) and displays the full monster stat block
- **SRD 2024** support (D&D 5.24) with automatic fallback to **SRD 2014**
- **Integrated initiative tracker**: monsters are added automatically with HP, AC and DEX modifier

### ⚔️ Battle
- Build complex encounters by selecting **multiple creature types** with custom quantities
- Search returns **all matching results** in a grid (e.g. searching "Goblin" shows Warrior, Boss, Sharpshooter…)
- **Multi-creature initiative tracker** with editable HP, AC and manual reordering
- **Dynamic stat block grid** on the right: one card per unique creature type selected

### 📋 Encounter Lists
- Create and manage **multiple themed lists** (forest, dungeon, city…)
- Each list supports up to 14 entries with automatic probability weighting based on 2d8
- Reorder entries visually

### 🧙 Party
- Save **player characters** with their fixed initiative bonuses
- Party members are automatically inserted into every initiative tracker

### ⚙️ Settings
- Configure die and trigger values for the encounter check roll
- **💾 Backup & Restore**: export all data (lists, party, settings) to a `.json` file and import it on any browser or device

---

## 🚀 How to Use

No installation needed.

1. Download `index.html`
2. Open it in any modern browser (Chrome, Edge, Firefox, Safari)
3. Everything works offline — except stat block loading, which requires an internet connection to query the Open5e API

---

## 💾 Data Persistence

Data (lists, party, settings) is saved in the browser's **localStorage** — it persists across sessions. To transfer data to another device or browser, use the **Export / Import** feature in the Settings page.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| [React 18](https://react.dev/) | UI and state management |
| [Babel Standalone](https://babeljs.io/) | In-browser JSX transpilation |
| [Open5e API](https://api.open5e.com/) | Monster stat blocks (SRD 2024 + 2014) |
| `localStorage` | Local data persistence |

No server, no build step, no dependencies to install — everything in a single ~2000-line HTML file.

---

## 📡 Open5e API

Monster stat blocks are fetched from [Open5e](https://open5e.com/):
- **Primary**: SRD 2024 via `api.open5e.com/v2/creatures/?document__key__in=srd-2024`
- **Fallback**: SRD 2014 via `api.open5e.com/v1/monsters/`

The **SRD 2024** or **SRD 2014** badge on the stat block indicates which version was found.

---

## 📄 License

Personal use. D&D content is covered by the [Systems Reference Document (SRD)](https://www.dndbeyond.com/srd) by Wizards of the Coast under Creative Commons license.
