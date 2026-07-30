# Project Status & Working Progress - Animal Crossing Wild World Deluxe

This document tracks the current development status, pending features, known bugs, and the roadmap for **Animal Crossing Wild World Deluxe**.

## 📊 Development Status Overview
* **Overall Progress:** ~45% Complete
* **Core Framework & Hacking Foundation:** Stable
* **Text & BMG Scripting:** In Progress (Active translation and script refinement)
* **Event & Feature Expansion:** Planning / Early Implementation

---

## 🚀 Upcoming Features & Additions (Todo)
* [ ] **Expanded Dialogue Archives (`.bmg`):** Complete the full overhaul and expansion of villager interaction scripts, seasonal festival dialogues, and special NPC responses.
* [ ] **Custom Event Modules:** Integrate specialized festive event strings (such as updated New Year's modules and holiday routines).
* [ ] **Item Database Tweaks:** Rebalance and expand item lists, custom catalog options, and store inventories inspired by *City Folk*.
* [ ] **Advanced Code Patches:** Implement community-driven code hooks (via `acww-hax`) for quality-of-life improvements on NDS hardware and emulators.

---

## 🛠️ Known Issues & Bugs to Fix
* [ ] **Character Limit Overflow:** Certain translated text strings exceed the original byte/character buffer limits in specific `.bmg` blocks, causing minor UI wrapping issues. *(Work in progress: trimming and checking exact line lengths)*.
* [ ] **Special Character Rendering:** Verify compatibility for accented characters across all mobile emulators (like Drastic and MelonDS) to prevent glyph corruption.
* [ ] **Patch Checksum Mismatch:** Ensure DeltaPatcher configurations correctly bypass strict CRC checks for regional ROM variations (US/EU).

---

## 🗺️ Roadmap / Next Milestones
1. **Phase 1 (Current):** Stabilize core text scripts and baseline delta patching pipeline.
2. **Phase 2:** Finalize custom villager dialogues and seasonal event string overhauls.
3. **Phase 3:** Comprehensive bug testing across real hardware (R4 flashcards) and modern emulators.
4. **Phase 4:** Official Stable Release (`v1.0`).

---
*Want to help us tackle items on this list? Check out our [Contribution Policy](ONCREDITS.md) and submit a Pull Request!*
