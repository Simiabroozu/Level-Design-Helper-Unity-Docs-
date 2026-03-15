# ProBuild Helper

**Version 1.0.0 · Unity 2021.3+**

A single-window toolkit that dramatically speeds up scene building. No configuration needed — open it and start working.

---

## Features

### 🏗 Placement
- Drop any prefab onto selected objects with one click
- Scatter N instances inside any object's bounds
- Optional random Y rotation and scale per spawn

### 🔲 Grid Snap
- Configurable cell size (any float)
- Visual grid overlay in Scene View
- One-click snap selection to grid
- Arrange selected objects in a row, column, or 2D grid

### 🎨 Brush Paint
- Multi-prefab palette (pick-and-preview thumbnails)
- Paint with LMB held in Scene View
- Adjustable radius, density, height offset
- Per-brush random rotation and scale ranges
- Layer mask to control what you paint onto

### 📐 Align
- Align min / center / max on any axis
- Ground objects via downward raycast (terrain-aware)
- Distribute objects with even spacing on X / Y / Z

### Right-Click Shortcuts (Hierarchy & Scene)
| Shortcut | Action |
|---|---|
| `Ctrl+G` | Ground selected objects |
| `Ctrl+Shift+G` | Group selected under empty parent |
| Right-click → LDH | Align Y, Replace with Prefab, Randomize rotation/scale |

---

## Installation

### Via Unity Package Manager (UPM)
1. Open **Window → Package Manager**
2. Click **+** → **Add package from disk**
3. Select the `package.json` file in this folder

### Manual
Copy the `LevelDesignHelper` folder into your project's `Assets/` directory.

---

## Opening the Window
**Tools → Level Design Helper** or **Ctrl+Shift+L**

---

## Requirements
- Unity 2021.3 LTS or newer
- No external dependencies

---

## Changelog

### 1.0.0
- Initial release
- Placement, Grid, Paint, Align tabs
- Right-click context menu shortcuts
- Persistent preferences (Edit → Preferences → Level Design Helper)

---

## License
See LICENSE.txt
