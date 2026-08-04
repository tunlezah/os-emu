# 🖥️ The OS Museum

**Interactive, in-browser simulations of classic operating systems — each one a single, self-contained HTML file.**

Nothing real runs. No VMs, no emulated CPUs, no ROMs, no installs. Every exhibit is a front-end
re-creation of the look, feel and quirks of a beloved OS: a museum piece you can actually click on.

## 🚀 Getting started

There is nothing to build and nothing to serve.

1. Clone or download this repository.
2. Open **[`index.html`](index.html)** in any modern browser — straight from disk (`file://`) works fine.
3. Pick an exhibit and boot it.

You can also open any exhibit's `.html` file directly; each one is fully standalone.

## 🗂️ The exhibits

| Year | Exhibit | Vendor | File | What you get |
|------|---------|--------|------|--------------|
| 1993 | **Windows for Workgroups 3.11** | Microsoft | [`win311.html`](win311.html) | Program Manager, File Manager and the classic 16-bit desktop on MS-DOS 6.22 |
| 1995 | **NeXTSTEP 3.3** | NeXT | [`nextstep.html`](nextstep.html) | The black slab: Workspace Manager, the Dock's ancestor, and the design language that shaped OS X |
| 1996 | **Novell NetWare 4.11 (IntranetWare)** | Novell | [`netware.html`](netware.html) | A server console simulation: MONITOR, NDS, volumes and console commands |
| 2000 | **BeOS R5** | Be Inc. | [`beos.html`](beos.html) | Tracker, Deskbar and the multimedia OS that was too good to live |
| 2001 | **Mac OS 9.2.2** | Apple | [`macos9.html`](macos9.html) | Platinum at its peak — the classic Finder's last stand |
| 2001 | **Mac OS X 10.0 “Cheetah”** | Apple | [`cheetah.html`](cheetah.html) | First-generation Aqua: lickable buttons, the original Dock, Unix underneath |
| 2001 | **IBM OS/2 Warp 4.52** | IBM | [`os2warp.html`](os2warp.html) | Boot Manager, CONFIG.SYS and the object-oriented Workplace Shell |

## ✨ How the exhibits are built

Every simulation in this museum follows the same rules:

- **One file.** All HTML, CSS and JavaScript live in a single `.html` document.
- **Zero dependencies.** No CDNs, no frameworks, no network requests, no assets to load.
- **Offline-first.** Opening the file from disk is the supported way to run it.
- **Simulation, not emulation.** These pages re-create interfaces and behaviour in the DOM;
  they don't execute original software or contain any copyrighted binaries.

The landing page ([`index.html`](index.html)) follows the same rules and renders its gallery
from a small data array, so the museum grows without any structural changes.

## ➕ Adding a new exhibit

New wings are always welcome. To add an OS:

1. **Create the simulation** as a single self-contained file, e.g. `amiga.html`, following
   the rules above (one file, no external resources, works from `file://`).
2. **Register it in the gallery** — open [`index.html`](index.html) and append one object to the
   `EXHIBITS` array near the top of the `<script>` block:

   ```js
   {
     file:   "amiga.html",
     name:   "AmigaOS 3.1",
     vendor: "Commodore",
     year:   1994,
     glyph:  "Amiga",                     // shown on the card's mini screen
     desc:   "Workbench, Guru Meditation and all.",
     accent: "#ff8a3d",                    // card accent colour
     bg:     "#1d1230",                    // mini-screen background
     tags:   "commodore amiga workbench"   // extra search keywords
   },
   ```

   Search, sorting and the card grid pick it up automatically — no other changes needed.
3. **Add a row** to the exhibits table in this README.

## 📄 Notes

- These simulations are fan-made tributes for educational and nostalgic purposes.
  All product names, logos and trademarks belong to their respective owners.
- Best experienced on a desktop browser — most of these interfaces predate touchscreens
  by a decade or more.
