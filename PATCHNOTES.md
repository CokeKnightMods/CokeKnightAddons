# CokeKnightAddons 0.17.5 — Resource Pack Menu Fix

- Downloaded cosmetic packages now appear as one **CokeKnightAddons** entry with the mod logo, instead of dozens of internal skin, model and sound archive names.
- Internal dependencies stay enabled when closing or refreshing the resource pack menu and when changing other resource packs.
- Existing skins, animations, sounds, loadouts and cached files are preserved. No cosmetic downloads are required again.
- Installed selections still load during normal startup, including offline. Cosmetic selection and optional cache cleanup continue to work through `/cs`.
- Retains the rendering improvements from 0.17.4.

Verified against 0.17.4 with 22 mounted packages: identical resource bytes and priority, all five weapon sound packages, menu save/rescan, cached selection, cleanup, offline restart and fresh installation. Rendering classes and all asset contents are unchanged.

---

# CokeKnightAddons 0.17.4 — Performance Update

- **124–177% higher average FPS** compared with 0.17.2 in the tested scenes.
- **AWP gameplay:** 164 → 413 FPS (**+151%**).
- **Full inventory:** 107 → 279 FPS (**+161%**).
- **Frequent item switching:** 248 → 554 FPS (**+124%**).
- **Multiple weapon models and active inspect animations:** 36 → 100 FPS (**+177%**).
- Improved 1% lows and lower P99 frame times across all four scenes.
- No reductions to model detail, texture quality or animation fidelity.
- Existing settings, loadouts and downloaded assets remain compatible and available offline.

Results are averages of three runs per scene at 1280×720 on a Ryzen 7 7800X3D and RTX 5070 Ti, with VSync and FPS limits disabled. Percentage gains use unrounded measurements. Local benchmarks do not guarantee identical gains on Hypixel or with other mod combinations. Active shader packs were not performance-benchmarked. Average peak process RAM was approximately 103–130 MiB higher than 0.17.2; this update does not claim lower RAM usage.
