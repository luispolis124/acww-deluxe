# acww-deluxe
Official repository for **Animal Crossing Wild World Deluxe**. Contains only patches (XDelta) and modding tools. No ROMs are included.
## 📌 About the Project
**Animal Crossing Wild World Deluxe** is a comprehensive custom mod project designed to enhance, expand, and modernize the original *Animal Crossing: Wild World* experience for the Nintendo DS (inspired by community projects like *Animal Crossing Deluxe* and *City Folk*).
### How It Works Under the Hood
 * **ROM Hacking & Binary Patches:** Instead of distributing copyrighted game binaries, the project utilizes binary delta patching (.xdelta). This modifies the game's internal data structures, text archives (.bmg), and engine code compiled from the ground up.
 * **Content Expansion & Customization:** It integrates restructured text scripts, custom event strings (such as updated festive dialogs like New Year's modules), revised item databases, and NPC tweaks to give the game a fresh, expanded feel while preserving its core charm.
 * **Compatibility:** The generated output patches cleanly onto standard US/EU retail NDS ROMs, ensuring seamless execution on real hardware via flashcards (like R4) or modern emulators (MelonDS, DeSmuME, Dr.astic).
> ⚠️ **IMPORTANT COPYRIGHT NOTICE:** This repository **does not** contain any ROM files. You must legally acquire your own clean ROM of *Animal Crossing: Wild World* (Nintendo DS) to apply these patches.
> 
## 🛠️ How to Apply the Patch
To play the mod, you will need:
 1. A clean ROM of *Animal Crossing: Wild World* (US/EU version).
 2. A patching tool (such as **DeltaPatcher**, **xdelta3**, or mobile/web-based patchers like **UniPatcher**).
### Step-by-Step Guide (PC & Mobile):
#### Option 1: On Mobile (Android)
 1. Download an application like **UniPatcher** from the Google Play Store.
 2. Ensure you have your clean *Animal Crossing: Wild World* ROM and the mod patch file (acww-deluxe.xdelta) saved on your device.
 3. Open **UniPatcher**:
   * **Patch file:** Select acww-deluxe.xdelta.
   * **ROM file:** Select your clean NDS ROM.
   * **Save as:** Choose your output destination (add .nds at the end, e.g., rom_final.nds).
 4. Tap **Apply patch**.
#### Option 2: On Computer
 1. Download a patching utility (e.g., **DeltaPatcher** for Windows or use **xdelta3** in the terminal).
 2. Open your patching tool:
   * **Original file / ROM:** Select your clean *Animal Crossing: Wild World* NDS ROM.
   * **Patch:** Select the downloaded mod patch file (acww-deluxe.xdelta).
   * **Apply Patch:** Click the apply button to generate your modified ROM (rom_final.nds).
 3. Run the patched ROM on your Nintendo DS flashcard (like R4) or an emulator (like MelonDS, DeSmuME, or DrStic).
## 📁 Repository Structure
 * /patches/ - Contains the versioned XDelta patch files.
 * /tools/ - Useful utilities and documentation for the modding process.
## 📜 Credits & Acknowledgments
 * Inspired by great community projects like *Animal Crossing Deluxe* (Cuyler) and *City Folk* (Aurum).
 * Special thanks to **TheGag96** for the **acww-hax** repository, used for technical foundations and game code modifications.
 * Developed by the community and fans of the franchise.
