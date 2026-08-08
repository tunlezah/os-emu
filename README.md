# 🖥️ The OS Museum

**Interactive, in-browser simulations of classic operating systems — each one a single, self-contained HTML file.**

Nothing real runs. No VMs, no emulated CPUs, no ROMs, no installs. Every exhibit is a front-end
re-creation of the look, feel and quirks of a beloved OS: a museum piece you can actually click on.

## 🚀 Getting started

**Visit the museum online:** [tunlezah.github.io/os-emu](https://tunlezah.github.io/os-emu/) — every exhibit, served straight from this repository via GitHub Pages.

Or run it locally — there is nothing to build and nothing to serve.

1. Clone or download this repository.
2. Open **[`index.html`](index.html)** in any modern browser — straight from disk (`file://`) works fine.
3. Pick an exhibit and boot it.

You can also open any exhibit's `.html` file directly; each one is fully standalone.

## 🗂️ The exhibits

| Year | Exhibit | Vendor | File | What you get |
|------|---------|--------|------|--------------|
| 1982 | **Commodore 64** | Commodore | [`c64.html`](c64.html) | The best-selling computer ever made, and the BASIC prompt *is* the operating system: blue-on-blue in under a second, then a real Commodore BASIC V2 with a full-screen editor, quote mode and two-character variable names. `10 PRINT CHR$(205.5+RND(1));` fills the screen with the maze, `POKE 53281,0` really does turn it black, the SID really does sing when you poke it, eight sprites fly and collide, raster bars work, a 1541 takes far too long, a tape fails on the first load, and `SYS 64738` wipes your unsaved program. Plus a 6510 core, a machine-code monitor on a cartridge, and a magazine type-in with a Proofreader |
| 1984 | **Apple Lisa Office System 3.1 (7/7)** | Apple | [`lisa.html`](lisa.html) | The birthplace of the desktop: stationery pads, Set Aside vs. Save & Put Away, the visible Clipboard, seven integrated tools, and soft power that restores everything — cursor and all |
| 1985 | **Windows 1.01** | Microsoft | [`win101.html`](win101.html) | Boot MS-DOS, type `WIN`: tiled windows that never overlap, MS-DOS Executive for a shell, monochrome Paint, Reversi and a hidden credits screen |
| 1993 | **SGI IRIX 4.0.5 + fsn** | Silicon Graphics | [`irix.html`](irix.html) | The workstation from the most famous computer scene in cinema — and none of it was invented. PROM power-on diagnostics with a working command monitor, IRIX kernel messages, the graphical login, then 4Dwm: Motif frames, the Toolchest, a three-button mouse, minimise-to-icon. Underneath is a real machine — `hinv`, `uname -a`, System V `ps -ef`, `/usr/people` for home directories, `man` pages, a genuine `csh` with history and pipes, and a small but sincere `vi`. Then launch **fsn**, the actual SGI 3D file browser: directories are pedestals, files are boxes coloured by *age*, wires arc between them, and selecting one flies you there. Create a file in the shell and go find it in 3D. On top of all that sits some in-house software running a dinosaur park — quit it and you are still at an ordinary UNIX box, which is the whole point |
| 1993 | **Windows for Workgroups 3.11** | Microsoft | [`win311.html`](win311.html) | Program Manager, File Manager and the classic 16-bit desktop on MS-DOS 6.22 |
| 1994 | **SunOS 4.1.4 / OpenWindows 3** | Sun Microsystems | [`sunos.html`](sunos.html) | The last of the BSD Suns on a SPARCstation: OpenBoot banner, BSD boot messages, `login:` on the glass console, then type `openwin` for the OPEN LOOK desktop — pushpinned menus, elevator scrollbars, the whole DeskSet, a working `vi` and `csh`, an NFS server that hangs and comes back, and Stop-A into the PROM at any moment (`go` resumes exactly where you were) |
| 1994 | **AmigaOS 3.1 / Workbench 3.1** | Commodore | [`amiga.html`](amiga.html) | Kickstart boot, right-button menus, drag-down screens, the Ram Disk, AmigaShell and the Guru Meditation |
| 1995 | **Windows 95 (RTM, 4.00.950)** | Microsoft | [`win95.html`](win95.html) | The day the modern desktop was invented: the brand-new Start button, teal desktop and solid-blue title bars, spatial folders and two-pane Explorer, the Recycle Bin, long filenames with 8.3 aliases, Solitaire/Minesweeper/FreeCell/Hearts, a windowed DOS 7 box, Control Panel with Device Manager and the draggable time-zone map, a survivable blue screen, and the orange "it's now safe to turn off your computer" — right-click absolutely everything |
| 1995 | **NeXTSTEP 3.3** | NeXT | [`nextstep.html`](nextstep.html) | The black slab: Workspace Manager, the Dock's ancestor, and the design language that shaped OS X |
| 1996 | **Novell NetWare 4.11 (IntranetWare)** | Novell | [`netware411.html`](netware411.html) · [`netware.html`](netware.html) | One server, two ways in. The full experience ([`netware411.html`](netware411.html)): DOS boot, the blue login screen, C-Worthy utilities — SYSCON, FILER, DSREPAIR, RCONSOLE — and a live network map. Or the console-only quick session ([`netware.html`](netware.html)): MONITOR, NDS, volumes and red-alert beeps on an 80×25 CRT. Both launch from the same card in the gallery |
| 2000 | **BeOS R5** | Be Inc. | [`beos.html`](beos.html) | Tracker, Deskbar and the multimedia OS that was too good to live |
| 2001 | **Mac OS 9.2.2** | Apple | [`macos9.html`](macos9.html) | Platinum at its peak — the classic Finder's last stand |
| 2001 | **Mac OS X 10.0 “Cheetah”** | Apple | [`cheetah.html`](cheetah.html) | First-generation Aqua: lickable buttons, the original Dock, Unix underneath |
| 2001 | **IBM OS/2 Warp 4.52** | IBM | [`os2warp.html`](os2warp.html) | Boot Manager, CONFIG.SYS and the object-oriented Workplace Shell |
| 2002 | **Plan 9 from Bell Labs, Fourth Edition** | Bell Labs | [`plan9.html`](plan9.html) | Unix's authors' second attempt at the same problem, and the museum's quietest revolution: everything really is a file, and every window really is a world. `cat /dev/mouse` streams your own mouse as text; `bind /tmp /bin` destroys `/bin` in one window while the next window's survives (that's a container, twenty years early); `ns` prints the namespace as the script that would rebuild it — which is why there's no `$PATH`. Sweep windows out with button 3 in rio, middle-click words to run them in acme, pipe `kill rio \| rc` and face the consequences, read yesterday's file at a path under `/n/dump`, run a shell on the CPU server with your own namespace imported, and import another machine's mouse to fight over the cursor. rc, sam, the plumber, a 9P trace window, stats, mothra and the catclock all work; three mouse buttons, chords, left-hand scrollbars and no keyboard shortcuts, exactly as Rob Pike intended. The exit panel (`cat /lib/exhibit`) tells the truth: the system lost, then UTF-8, `/proc`, namespaces and Go quietly won |
| 2012 | **Windows 8 (RTM, build 9200)** | Microsoft | [`win8.html`](win8.html) | Two operating systems bolted together, exhibited as shipped — before 8.1 walked any of it back. Boot past the lock screen (password, PIN, or a real picture password with taps, lines and circles), land on a Start screen of live tiles that flip and breathe, and try semantic zoom (Ctrl+scroll) — still one of the great interactions. Charms hide off the right edge, commands hide in app bars, apps close by dragging them off the bottom of the screen, and Snap gives you exactly two apps in a 320px split (at 1024×768 it refuses, authentically). Behind it all sits the desktop — demoted to a tile — with a flat, ribboned Explorer, the heat-mapped Task Manager, both Internet Explorers, and a bottom-left corner that is conspicuously, historically bare. Shutdown is four levels deep and the exhibit counts how many clicks it takes you; the sad-face blue screen is available on request (`crash` in Command Prompt), and the GodMode folder trick genuinely works |
| 2023 | **IBM z/OS 3.1** | IBM | [`zos.html`](zos.html) | A 3270 terminal on a living mainframe: IPL, VTAM logon, TSO/ISPF, the editor, JCL, JES2, SDSF, REXX, USS and the MVS operator console — uniquely in this museum, not a memory but a description of next Tuesday |
| 2025 | **SymbOS 4.0** | Prodatron / SymbiosiS | [`symbos.html`](symbos.html) | A Win9x-grade multitasking desktop on a 4 MHz Z80: pick your machine (CPC, MSX2, Spectrum Next, PCW), then run SymAmp chiptunes, a windowed raycaster and a file copy at once — all accounted for in 16K banks. Not a memory either: the real thing is free at symbos.de |

## ✨ How the exhibits are built

Every simulation in this museum follows the same rules:

- **One file.** All HTML, CSS and JavaScript live in a single `.html` document.
- **Zero dependencies.** No CDNs, no frameworks, no network requests, no assets to load.
- **Offline-first.** Opening the file from disk is the supported way to run it.
- **Simulation, not emulation.** These pages re-create interfaces and behaviour in the browser;
  they don't execute original software or contain any copyrighted binaries. Where an exhibit
  goes deeper — the C64's BASIC interpreter, its video chip, its sound chip and its 6510 —
  every byte of it is written from scratch to behave like the real thing.

The landing page ([`index.html`](index.html)) follows the same rules and renders its gallery
from a small data array, so the museum grows without any structural changes.

## ➕ Adding a new exhibit

New wings are always welcome. To add an OS:

1. **Create the simulation** as a single self-contained file, e.g. `solaris.html`, following
   the rules above (one file, no external resources, works from `file://`).
2. **Register it in the gallery** — open [`index.html`](index.html) and append one object to the
   `EXHIBITS` array near the top of the `<script>` block:

   ```js
   {
     file:   "solaris.html",
     name:   "Solaris 2.6",
     vendor: "Sun Microsystems",
     year:   1997,
     glyph:  "Sun",                        // shown on the card's mini screen
     desc:   "CDE, OpenWindows and all.",
     accent: "#7f7fff",                    // card accent colour
     bg:     "#301a50",                    // mini-screen background
     tags:   "sun solaris sparc cde"       // extra search keywords
   },
   ```

   Search, sorting and the card grid pick it up automatically — no other changes needed.
   If one exhibit ships several builds, add an optional `variants: [{file, label}, …]`
   array to the entry — the card then shows one launch link per build (see NetWare).
3. **Add a row** to the exhibits table in this README.

## 📄 Notes

- These simulations are fan-made tributes for educational and nostalgic purposes.
  All product names, logos and trademarks belong to their respective owners.
- Best experienced on a desktop browser — most of these interfaces predate touchscreens
  by a decade or more.
