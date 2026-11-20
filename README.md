# Nesting Engine

Sheet and roll nesting for **Rhino 8** (and **Rhino 7**, see below), made by Canvas and Covers Whangarei.

Nests parts onto sheets (several sizes) or fabric rolls (several widths), using only moves and rotations – parts are never changed or mirrored – and exports the nest as Rhino 8, Rhino 7 or DXF R12 for the CNC.

## Install (once per PC)

1. You need **Rhino 8, version 8.37 or newer** (Help → About Rhinoceros; Help → Check for Updates if older).
2. Download the latest package: **[Download Nesting Engine 1.2.10](https://github.com/brendan608/nesting-engine/raw/main/releases/nestingengine-1.2.10-rh8_37-win.yak)**
3. Open Rhino 8 and **drag the downloaded `.yak` file onto the Rhino viewport**.
   (Double-clicking the file does not work – Rhino asks for the file instead. If that happens, click *Browse* and pick it.)
4. Close Rhino and open it again.
5. Type `NestingEngine` (or click the Nesting Engine tab in the toolbar at the top). The panel docks itself on the left the first time.

## Updates

Nothing to do. Each time Rhino starts, the Nesting Engine checks here for a newer version and installs it; Rhino then asks for a restart, and the new version runs from the next start.

## Rhino 7 version

A separate package for PCs that only have **Rhino 7** (any Rhino 7 version). Same panel and same nesting; it exports Rhino 7 or DXF R12 (Rhino 7 cannot write Rhino 8 files). **Only install it in Rhino 7** – in Rhino 8 use the normal package above.

1. Download it: **[Download Nesting Engine for Rhino 7 – 1.2.10](https://github.com/brendan608/nesting-engine/raw/main/releases/nestingengine-rhino7-1.2.10-rh7_0-win.yak)**
2. Open Rhino 7 and **drag the downloaded `.yak` file onto the Rhino viewport**.
   If Rhino 7 does not install it that way: close Rhino 7, open the Windows *Command Prompt* and type (all on one line, with your own Downloads folder):
   `"C:\Program Files\Rhino 7\System\Yak.exe" install --source "%USERPROFILE%\Downloads" NestingEngine-Rhino7`
3. Close Rhino 7 and open it again.
4. Type `NestingEngine`. The panel opens beside the viewport (drag its tab where you like it).

Updates: like the Rhino 8 version, it checks here once each time Rhino 7 starts ([latest-rhino7.json](latest-rhino7.json)) and installs a newer Rhino 7 package by itself; restart Rhino 7 to use it.

## Versions

[latest.json](latest.json) names the current Rhino 8 version and [latest-rhino7.json](latest-rhino7.json) the current Rhino 7 version; every package is in [releases](releases/) (Rhino 7 packages are the `nestingengine-rhino7-…` files).
