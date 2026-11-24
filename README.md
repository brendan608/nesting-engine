# Nesting Engine

Sheet and roll nesting for **Rhino 8 and Rhino 7**, made by Canvas and Covers Whangarei.

Nests parts onto sheets (several sizes) or fabric rolls (several widths), using only moves and rotations – parts are never changed or mirrored – and exports the nest as a drawing (Rhino 8, Rhino 7 or DXF R12) or as a cutter file for CutPilot (.anc).

## Install (once per PC)

One file for both Rhino 8 and Rhino 7 – it runs the right version by itself.

1. Download it: **[Download Nesting Engine 1.3.1 (Rhino 7 and Rhino 8)](https://github.com/brendan608/nesting-engine/raw/main/releases/nestingengine-1.3.1-rhino7-and-rhino8.yak)**
2. Open Rhino and **drag the downloaded `.yak` file onto the Rhino viewport**.
   (Double-clicking the file does not work – Rhino asks for the file instead. If that happens, click *Browse* and pick it.)
3. Close Rhino and open it again.
4. Type `NestingEngine`. In Rhino 8 the panel docks itself on the left and has a Nesting Engine tab in the toolbar at the top; in Rhino 7 it opens as a window (drag it where you like it).

Already have the old separate Rhino 7 package (NestingEngine-Rhino7)? Install this one anyway: it removes the old one by itself (restart Rhino 7 once more when it says so).

## Updates

Nothing to do. Each time Rhino starts, the Nesting Engine checks here for a newer version and installs it; Rhino then asks for a restart, and the new version runs from the next start.

## Nesting Engine Desktop (Windows, no Rhino needed) - beta

The same nesting as a stand-alone Windows program: opens Rhino (.3dm) and DXF drawings, nests them, and exports Rhino 8 / Rhino 7 / DXF R12 drawings and CutPilot cutter files. Jobs can be saved as `.nej` files.

**Install (once per PC):** download **[Install-Nesting-Engine-Desktop.cmd](https://github.com/brendan608/nesting-engine/releases/latest/download/Install-Nesting-Engine-Desktop.cmd)** and double-click it. It downloads the program from here and installs it for your Windows user (no administrator rights), with a desktop shortcut. If Windows shows "Windows protected your PC", click *More info* then *Run anyway*.

Windows 10 or 11 (64-bit). Nothing else is needed.

**Updates:** automatic. Each time the program starts it checks here for a newer version, downloads it and offers to restart into it (or installs it when you close the program).

[desktop-latest.json](desktop-latest.json) names the current desktop version; the program files are on the [desktop releases](https://github.com/brendan608/nesting-engine/releases).
## Versions

[latest.json](latest.json) names the current version; every package is in [releases](releases/). Older versions had separate Rhino 8 (`…-rh8_37-win.yak`) and Rhino 7 (`nestingengine-rhino7-…`) packages.
