# Text-Adventure-2025

A Python text-adventure project I’m using to practice Python fundamentals and build a portfolio-ready project over multiple phases.

This repo includes:
- A completed playable **Phase 1** version
- A work-in-progress **Phase 2** version (gameplay systems + refactor direction)
- Planning documents and original design spreadsheets (map + data)

---

## How to Run (Local Jupyter)

### Requirements
- Python 3.12+ (3.13/3.14 are fine)
- Jupyter Notebook

### Install Jupyter
```bash
python -m pip install notebook
jupyter notebook
Open and run one of these notebooks

text_adventure_v1_0.ipynb — Phase 1 playable

text_adventure_v2_0.ipynb — Phase 2 WIP

Tip: In Jupyter, use Run → Run All Cells to start the game.
If a cell uses input(), the notebook will pause and wait for your input below the cell.

Repo Files (Quick Guide)
Playable / Code

text_adventure_v1_0.ipynb — Phase 1 completed playable version

text_adventure_v2_0.ipynb — Phase 2 work-in-progress notebook (current development)

Documentation / Plans

Phase_1_Project_Plan.docx — Phase 1 plan / closeout notes

Phase_2_Project_Plan.docx — Phase 2 plan (milestones like 2.1, 2.2, etc.)

README.md — project overview + roadmap

Design / Data (original planning spreadsheets)

text_adventure_map_v1_0.xlsx — Room map / layout reference

text_adventure_data_file_v1_0.xlsx — Rooms/items/enemies planning data reference

Roadmap
Phase 1 (Complete)

Working text-adventure loop

Commands supported (example set):

move (go north/south/east/west)

inspect room

pick up items

use items

inventory

back

Rooms, items, and enemies supported in-game

Phase 2 (In Progress)

Goal: Improve gameplay systems and refactor toward a cleaner architecture that’s easier to expand.

Planned improvements include:

Player health (start at 100) + random damage (no instant death)

Status command

Better command parsing + error handling (invalid inputs, missing items, etc.)

Convert rooms/player into classes

JSON-driven content (rooms/items/enemies)

Split into modules (rooms.py, player.py, combat.py, items.py, game.py)

Phase 3 (Dream)

Simple UI / visuals layer (app or lightweight UI wrapper)

Optional audio playback / TTS integration (ex: ElevenLabs clips)

Versioning (How I’m tracking progress)

Development happens in the Phase 2 notebook (text_adventure_v2_0.ipynb)

Milestones (like 2.1) are committed to GitHub so progress is visible in history
(optionally duplicated as a new milestone file later if needed)

License

(Planned) MIT License for code.
Any future audio/demo assets (TTS clips, images, etc.) will be handled separately if added.



