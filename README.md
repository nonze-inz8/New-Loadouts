# New Loadouts

[![Game](https://img.shields.io/badge/Game-Nuclear%20Option-red.svg)](https://store.steampowered.com/app/2168680/Nuclear_Option/)
[![Framework](https://img.shields.io/badge/Framework-BepInEx%205-blue.svg)](https://github.com/BepInEx/BepInEx)
[![Version](https://img.shields.io/badge/Version-6.0.0-green.svg)](https://github.com/Nonze/New-Loadouts/releases)
[![Author](https://img.shields.io/badge/Author-Nonze-purple.svg)](#)

A complete overhaul of the hangar loadout interface and aircraft customization system for **Nuclear Option**. 

This mod replaces the cluttered default dropdown menus with intuitive, interactive **3D world-space markers** placed directly on the airframe's hardpoints, introduces a clean **6-column categorized weapon catalog**, a persistent **Favorites system**, per-aircraft **Loadout Presets**, and a minimal, clutter-free hangar view.

---

## Key Features

### 1. Interactive 3D Hardpoint Markers
* **Direct Airframe Interaction:** Replaces bottom menus with responsive 3D circular markers anchored directly to physical weapon mounts.
* **Smart Status Indicators:**
  * **Green Dot:** Hardpoint is currently armed.
  * **Red Outline:** Hardpoint is empty/unarmed.
  * **Grey Dot:** Hardpoint is blocked or conflicted by adjacent mounts.
* **Comprehensive TTX Tooltips:** Hovering over any hardpoint displays dynamic weapon specifications (Seeker Guidance, Range, Armor Piercing, Blast Yield, Mass, and Unit Cost) without text clipping.

### 2. Full-Screen Weapon Catalog (6 Columns)
* **High-Density Grid:** Replaces long, scrolling single-column lists with an optimized, responsive 6-column matrix.
* **Multi-Tier Filtering:**
  * **Role:** Air-to-Air, Air-to-Ground, Ground-to-Air, Utility & Cargo.
  * **Type:** Guided Missiles, Unguided Rockets, Free-fall Bombs, Glide/Laser Bombs, Guns & Autocannons, Tactical/Strategic Nuclear weapons.
  * **Range:** Short (< 8 km), Medium (8–25 km), Long (25–60 km), and Strategic (> 60 km).
* **Real-time Search:** Extended search bar with instant filtering across weapon designations and metadata.

### 3. Integrated Favorites System
* **Quick Pinning:** Mark any weapon with the `☆` icon directly from its catalog card.
* **Purple Neon Accent:** Pinned weapons receive an illuminated purple border.
* **Persistent Placement:** Favorited ordnance automatically pins to the top row (directly after native gear) upon reopening the catalog. Preferences are permanently saved to `BepInEx/config/LoadoutFavorites.json`.

### 4. Native Ordnance Highlighting
* Stock aircraft equipment and dedicated slots (such as the carrier **Tail Hook** and internal **Autocannons**) are highlighted with a distinct **Orange Accent** and pinned first to prevent endless searching.

### 5. Aircraft Loadout Presets
* Save, overwrite, and quickly deploy custom loadout configurations per aircraft.
* Clean dropdown management widget docked directly in the bottom-right corner of the loadout selector.
* Configurations persist inside `BepInEx/config/LoadoutPresets.json`.

### 6. Clean Hangar UI & Aircraft Quick-Switch
* Hides unnecessary inspection panels and background selectors.
* Fully integrates aircraft switching by making the top **Aircraft Name** text clickable.
* Retains vanilla functionality: **FLY** button, gross weight calculations, fuel slider, and telemetry remain fully intact.

---

## Installation

### Prerequisites
* Ensure you have [BepInEx 5.4.x (x64)](https://github.com/BepInEx/BepInEx/releases) installed in your game directory.

### Setup
1. Download the latest `NewLoadouts.dll` from the [Releases](https://github.com/Nonze/New-Loadouts/releases) section.
2. Navigate to your Nuclear Option installation folder:
   ```text
   ...\Steam\steamapps\common\Nuclear Option\BepInEx\plugins\
