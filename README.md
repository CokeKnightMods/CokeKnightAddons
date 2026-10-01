# CokeKnightAddons

Client-side CS-inspired cosmetics for Hypixel SkyBlock, with customizable loadouts, viewmodels, knife inspections and MVP music.

## Download

**[Download CokeKnightAddons 0.17.0](https://github.com/CokeKnightMods/CokeKnightAddons/releases/download/v0.17.0/CokeKnightAddons-0.17.0-MC26.1.2.jar)** · [Release notes and installation](https://github.com/CokeKnightMods/CokeKnightAddons/releases/tag/v0.17.0)

Requires **Minecraft 26.1.2, Fabric Loader 0.19.3 or newer, and Java 25**.
Put the JAR in your instance's `mods` folder. Keep only one version of the mod.
Fabric API, Fabric Language Kotlin and Pack Disabler are bundled.

## In game

Open **`/cs`** to choose skins, gloves and skin tone; configure your viewmodel,
inspect animations and audio; assign cosmetics to custom items; and manage downloads.
Existing settings remain compatible. All UI labels are in English.

- **38.40 MB base download.** All catalogue thumbnails are included.
- 860 individual cosmetic packages are hosted separately. Choosing a cosmetic downloads only that package and required shared files.
- Models, textures, animations, normal/rare inspect loops and handling sounds load together. Missing assets use the Pack Disabler fallback.
- Downloads run in the background, are SHA-256 checked, and remain cached for offline use. Automatic cleanup is optional and off by default.
- Knife model/skin selection, per-item gloves, ultimate-enchantment and dagger-attunement assignments, custom item mappings and first-person previews.
- Configurable inspect loops, rare-inspect chance and inspect keybind; gameplay actions retain priority.

## MVP music

Open **`/cs` → Sounds & MVP Music → Download** next to a track.
All **113 catalogue tracks** have individual optional downloads. Each row shows progress or Retry on failure.
Downloaded tracks remain in `config/CokeKnightAddons/mvp/audio/` and work offline.
Manual Ogg Vorbis import remains available, and downloads preserve existing imports.

Select one or more tracks, set each volume, and use Preview. Playback after successful Kuudra and Dungeon runs can be toggled separately.
The duration is configurable from 5 to 15 seconds, with a short fade-out; shorter tracks are not looped.

For manual installation, **[download the optional complete MVP ZIP](https://github.com/CokeKnightMods/CokeKnightAddons/releases/download/mvp-tracks-1/CokeKnightAddons-MVP-Tracks.zip)** and extract it into the instance folder. This ZIP does not go in `mods`.

No GitHub account is required to download or use the mod. Do not download the whole asset branches.
The base JAR contains no optional cosmetic models or music recordings.
This is not an official Valve, Mojang, Microsoft or Hypixel product. See the release's third-party notices.

## Verification and limits

Tested in a clean local Minecraft client: anonymous HTTPS downloads, resource reload,
required inspect animation and sound availability, MVP download/preview, persisted settings,
offline restart, malformed downloads, SHA-256 rejection, retry and preservation of manual music imports.
All 860 asset packages were checked for integrity and dependency completeness.
Other operating systems and arbitrary mod/shader combinations have not been exhaustively tested.
This release does not introduce gameplay automation or server-side behavior changes.
