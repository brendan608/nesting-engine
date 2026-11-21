# Nesting Engine

Sheet and roll nesting for **Rhino 8 and Rhino 7**, made by Canvas and Covers Whangarei.

Nests parts onto sheets (several sizes) or fabric rolls (several widths), using only moves and rotations – parts are never changed or mirrored – and exports the nest as a drawing (Rhino 8, Rhino 7 or DXF R12) or as a cutter file for CutPilot (.anc).

## Install (once per PC)

One file for both Rhino 8 and Rhino 7 – it runs the right version by itself.

1. Download it: **[Download Nesting Engine 1.3.0 (Rhino 7 and Rhino 8)](https://github.com/brendan608/nesting-engine/raw/main/releases/nestingengine-1.3.0-rhino7-and-rhino8.yak)**
2. Open Rhino and **drag the downloaded `.yak` file onto the Rhino viewport**.
   (Double-clicking the file does not work – Rhino asks for the file instead. If that happens, click *Browse* and pick it.)
3. Close Rhino and open it again.
4. Type `NestingEngine`. In Rhino 8 the panel docks itself on the left and has a Nesting Engine tab in the toolbar at the top; in Rhino 7 it opens as a window (drag it where you like it).

Already have the old separate Rhino 7 package (NestingEngine-Rhino7)? Install this one anyway: it removes the old one by itself (restart Rhino 7 once more when it says so).

## Updates

Nothing to do. Each time Rhino starts, the Nesting Engine checks here for a newer version and installs it; Rhino then asks for a restart, and the new version runs from the next start.

## Versions

[latest.json](latest.json) names the current version; every package is in [releases](releases/). Older versions had separate Rhino 8 (`…-rh8_37-win.yak`) and Rhino 7 (`nestingengine-rhino7-…`) packages.
