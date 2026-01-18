# Vampires vs. Zombies Text Adventure (Python)

A terminal-based text adventure game prototype built in Python.  
This repo documents the project in phases and is being expanded into a data-driven engine (JSON) with a future TTS/audio pipeline.

---

## Project Status

### ✅ Phase 1 (Completed)
**Finished version:** `Text Adventure 1.0`

Phase 1 includes:
- Room navigation (N/E/S/W)
- Inspect/explore descriptions
- Inventory + item pickup/use
- Enemy encounters (prototype combat rules)
- World design and planning artifacts

**Phase 1 documentation:** `Phase 1 Project Plan.docx`

---

### 🛠️ Phase 2 (In Progress)
**Current work file:** `Text_Adventure_2_0.ipynb`

Phase 2 goals (planned):
- Player health (start at 100) + random damage (no instant death)
- `status` command (health/location/inventory)
- `back` command (room history)
- Convert world content to JSON and load it dynamically
- Add validation checks (broken room links, missing rooms, invalid values)
- Prepare output for future TTS (centralized output/logging)

---

## How to Run (Phase 1)
1. Download or clone this repo
2. Run the Phase 1 script:
   - Open `Text Adventure 1.0`
   - Run it with Python (example):
     ```bash
     python "Text Adventure 1.0"
     ```
   *(If your Phase 1 file is actually `.py`, rename this command accordingly.)*

---

## Repo Files (Quick Guide)
- `text_adventure_v1_0.ipynb` — Phase 1 completed playable version
- `text_adventure_v2_0.ipynb` — Phase 2 work-in-progress notebook
- `Phase 1 Project Plan.docx` — Phase 1 plan/closeout documentation
- `README.md` — overview + roadmap

---

## Roadmap
- **Phase 2:** JSON-driven content + improved gameplay systems + TTS-ready output
- **Phase 3 (Dream):** Simple UI / app wrapper with visuals + audio playback

---

## License
(Planned) MIT License for code. Audio/demo assets will be handled separately if added.
