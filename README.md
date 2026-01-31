# Text-Adventure-2025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iTryKetchup/Text-Adventure-2025/blob/main/text_adventure_stable.ipynb)

---
Text Adventure (Python)

A terminal-based text adventure RPG built in Python as a **coding practice + portfolio project**.  
The goal is to evolve from a Phase 1 prototype into a **stable, data-driven engine (JSON)** with a **future TTS/audio pipeline**.

---

## Project Status

### ✅ Phase 1 (Completed)
Phase 1 is a playable prototype with:
- Room navigation (N/E/S/W)
- Inspect/explore descriptions
- Inventory + item pickup/use
- Enemy encounters (prototype rules)
- Planning artifacts + world design work

Primary file:
- `text_adventure_v1_0.ipynb`

Documentation:
- `Phase_1_Project_Plan.docx`

---

### 🛠️ Phase 2 (In Progress)
Phase 2 upgrades the prototype into a more professional, maintainable project:
- Player health system (start at **100**)
- Non-lethal combat with **random damage**
- `status` command (health / location / inventory)
- `back` command (room history)
- Stronger command parsing + error handling
- Begin converting world content to **JSON** (data-driven loading)
- Start organizing content for a future **TTS-ready workflow**
- Add basic unit tests for reliability

Primary file:
- `text_adventure_v2_0.ipynb`

Documentation:
- `Phase_2_Project_Plan.docx`

---

## Repo Files (Quick Guide)

| File | Purpose |
|------|---------|
| `README.md` | Project overview + roadmap |
| `Phase_1_Project_Plan.docx` | Phase 1 plan/closeout documentation |
| `Phase_2_Project_Plan.docx` | Phase 2 implementation plan (systems + refactor + JSON + tests) |
| `text_adventure_v1_0.ipynb` | Phase 1 playable notebook |
| `text_adventure_v2_0.ipynb` | Phase 2 work-in-progress notebook |
| `text_adventure_map_v1_0.xlsx` | World map / room layout planning (spreadsheet) |
| `text_adventure_data_file_v1_0.xlsx` | World content planning (rooms/items/enemies) |

> Note: The `.xlsx` files are planning artifacts used to build/validate the world before exporting to JSON.

---

## How to Run

### Option A — Run in Google Colab (easy)
Open a notebook directly in Colab:
- Phase 1: https://colab.research.google.com/github/iTryKetchup/Text-Adventure-2025/blob/main/text_adventure_v1_0.ipynb
- Phase 2: https://colab.research.google.com/github/iTryKetchup/Text-Adventure-2025/blob/main/text_adventure_v2_0.ipynb

Then click **Runtime → Run all** (or run cell-by-cell).

### Option B — Run locally (Jupyter)
**Requirements**
- Python 3.10+ recommended
- Jupyter Notebook or JupyterLab

**Steps**
1. Clone the repo:
   ```bash
   git clone https://github.com/iTryKetchup/Text-Adventure-2025.git
   cd Text-Adventure-2025
Install Jupyter (if needed):

bash
Copy code
pip install notebook
Start Jupyter:

bash
Copy code
jupyter notebook
Open either:

text_adventure_v1_0.ipynb (Phase 1)

text_adventure_v2_0.ipynb (Phase 2)

Current / Planned Commands
Phase 1 includes core navigation + interaction commands.

Phase 2 adds/standardizes:

status → show health, location, inventory

back → return to previous room (history stack)

Improved parsing:

normalize input with strip().lower()

support “verb + object” inputs like go north, pick up knife

Exact command words may evolve as Phase 2 refactors into cleaner handlers.

Phase 2 Roadmap (Implementation Milestones)
Milestone 1 — Core Gameplay Systems
Health system (max 100)

Random enemy damage (non-lethal model)

status command

back command (room history)

Starting items (knife + bat)

Health packs (+20), with planned flashlight reveal mechanic

Milestone 2 — Refactor to Classes + Modules
Refactor notebook logic into a maintainable structure:

Room class (name, description, items, exits, enemy, etc.)

Player class (health, inventory, history)

Split into modules (planned):

game.py, rooms.py, player.py, items.py, combat.py

Milestone 3 — JSON World Foundation
Move toward a data-driven world:

Draft JSON schema for rooms/items/enemies

Loader reads JSON and builds room objects/dicts

Validation checks (broken links, missing rooms, invalid exits)

Milestone 4 — TTS Prep (Foundation)
Prepare for future TTS integration:

Clean speech lines (narration/dialog)

Add TTS filename fields to content data

Export “speech line list” for later ElevenLabs generation

Keep repo audio footprint small (demo pack only)

Milestone 5 — Testing
Add 5–10 unit tests (planned targets):

Every exit points to a valid room

back returns correctly

Healing never exceeds max health (100)

Damage reduces health correctly

Design Goals
Stable gameplay loop (no crashes, helpful errors)

Data-driven content (JSON-based world loading)

Clean architecture (classes + modules, easy expansion)

Future-ready for audio/UI (TTS-friendly output workflow)

What’s Next (Phase 3 “Dream”)
Simple UI wrapper (desktop/web)

Audio playback (TTS narration/dialog)

Optional save/load system

Expanded combat and encounter logic

License
Planned: MIT License for code.
Audio/demo assets (if added later) may be licensed separately.

Author
Nicholas Brown
Project repo: https://github.com/iTryKetchup/Text-Adventure-2025
