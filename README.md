# Text-Adventure-2025 (Python)

A terminal-style **text adventure** project built as a practical way to learn Python by building something real.
This repo is organized in phases:

- ✅ **Phase 1:** playable prototype
- 🛠️ **Phase 2:** in progress (health/combat + JSON + better structure)
- 🌙 **Phase 3 (Dream):** simple UI/app wrapper with visuals + audio playback (TTS)

---

## Project Status

### ✅ Phase 1 (Completed)
**Playable prototype:** `text_adventure_v1_0.ipynb`

Phase 1 includes:
- Room navigation (`go north/south/east/west`)
- Inspect/look descriptions
- Inventory + item pickup/use
- Enemy encounters (prototype logic)
- Basic gameplay loop

Documentation:
- `Phase_1_Project_Plan.docx`

---

### 🛠️ Phase 2 (In Progress)
**Current work:** `text_adventure_v2_0.ipynb`

Phase 2 goals (planned/being built):
- Player health (start at 100)
- Random damage (no instant death)
- `status` command (health / location / inventory)
- `back` command (room history)
- Convert world content to **JSON** + load dynamically
- Cleaner command parsing + better error handling
- TTS-ready output planning (keep demo audio clips under 20)

Documentation:
- `Phase_2_Project_Plan.docx`

---

## How to Run

### Option A — Run in Google Colab (easiest)
1. Open `text_adventure_v1_0.ipynb`
2. Click **Open in Colab** (or upload to Colab)
3. Run the cells top-to-bottom
4. Use the input prompts to play

### Option B — Run locally in Jupyter
1. Install Jupyter:
   ```bash
   pip install notebook
