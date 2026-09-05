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

**The launcher** has a search box, sorting by year or by name, and a theme switch: **Dark**,
**Light**, **System** (follows your OS setting) or **Themed**, which dresses the whole page as one
of five exhibits' operating systems — Windows 95, Windows XP, Mac OS 9, Mac OS X Tiger or
Windows 8 — chosen at random on every visit. Click *Themed* again for another one. Your choice is
remembered in the browser. Every card is the same height and shows the first few lines of its
blurb; **more…** opens the rest in place.

## 🗂️ The exhibits

The collection hangs in **two wings**, and every exhibit belongs to exactly one of them:

- **🖥️ Desktop** — operating systems designed for a desk: workstations, home computers, servers,
  luggables and terminals. Keyboard-and-mouse or command-line first.
- **📱 Mobile** — operating systems designed for the hand: palmtops, PDAs, phones and tablets.
  Stylus, keypad or touch first; battery-powered; instant-on.

### Which wing?

Categorise by the **device class the OS was designed for**, never by the hardware it happens to
be demoed on (everything here runs in a browser anyway). Windows, Mac OS, Amiga, BeOS, OS/2, the
UNIX desktops and the mainframes are Desktop; Newton, Palm, Windows CE, Symbian, EPOC, BlackBerry
and early iPhone OS or Android are Mobile. Edge cases, settled in advance: **tablets are Mobile**
(touch and battery decide it); **a luggable or sub-notebook running a desktop OS is Desktop**; **an
OS with both editions is placed per edition** — Windows 95 is Desktop, Windows CE is Mobile.

Each row below is a one-line summary. The full placard for every exhibit — what the simulation
reproduces, why the system mattered, what to try first — lives in
[`docs/placards.md`](docs/placards.md); the exhibit's name links straight to it.

### 🖥️ Desktop

| Year | Exhibit | Vendor | File | What you get |
|------|---------|--------|------|--------------|
| 1981 | **[Xerox 8010 Information System (Star)](docs/placards.md#xerox-8010-information-system-star)** | Xerox | [`star.html`](star.html) | The machine almost everything on your screen came from: 1024 × 808 one-bit pixels, SELECT and ADJUST, nine universal command keys — and UNDO, in 1981 |
| 1982 | **[Commodore 64](docs/placards.md#commodore-64)** | Commodore | [`c64.html`](c64.html) | The best-selling computer ever made, where the BASIC prompt *is* the operating system: a real Commodore BASIC V2, POKE the SID, wait for the 1541 |
| 1984 | **[Apple Lisa Office System 3.1 (7/7)](docs/placards.md#apple-lisa-office-system-31-77)** | Apple | [`lisa.html`](lisa.html) | The birthplace of the desktop: stationery pads, Set Aside vs. Save & Put Away, seven integrated tools and soft power that restores everything — cursor and all |
| 1985 | **[Windows 1.01](docs/placards.md#windows-101)** | Microsoft | [`win101.html`](win101.html) | Boot MS-DOS, type `WIN`: tiled windows that never overlap, MS-DOS Executive for a shell, monochrome Paint, Reversi and a hidden credits screen |
| 1988 | **[GEOS 2.0](docs/placards.md#geos-20)** | Berkeley Softworks | [`geos.html`](geos.html) | A complete WIMP desktop with a WYSIWYG word processor on a 1 MHz 6510 with 64K — possible only because it replaced the disk drive's firmware while it was running |
| 1989 | **[Atari TOS 1.04 + GEM](docs/placards.md#atari-tos-104--gem)** | Atari | [`ataritos.html`](ataritos.html) | A controlled experiment: Atari's GEM in ROM, with overlapping windows and a trash can, beside Digital Research's post-lawsuit GEM Desktop 2.0 without them |
| 1992 | **[RISC OS 3.11](docs/placards.md#risc-os-311)** | Acorn | [`riscos.html`](riscos.html) | No menu bar anywhere — every menu comes from the middle mouse button — and files are saved by dragging their icon, because there has never been a path field |
| 1993 | **[SGI IRIX 4.0.5 + fsn](docs/placards.md#sgi-irix-405--fsn)** | Silicon Graphics | [`irix.html`](irix.html) | The workstation from cinema's most famous computer scene, all of it real: PROM monitor, 4Dwm, the Toolchest, and fsn, the actual 3D file browser |
| 1993 | **[Windows for Workgroups 3.11](docs/placards.md#windows-for-workgroups-311)** | Microsoft | [`win311.html`](win311.html) | Program Manager, File Manager and the classic 16-bit desktop on MS-DOS 6.22 |
| 1994 | **[SunOS 4.1.4 / OpenWindows 3](docs/placards.md#sunos-414--openwindows-3)** | Sun Microsystems | [`sunos.html`](sunos.html) | The last of the BSD Suns: OpenBoot banner, `login:` on the glass console, then `openwin` for OPEN LOOK — pushpins, elevator scrollbars and an NFS server that hangs |
| 1994 | **[AmigaOS 3.1 / Workbench 3.1](docs/placards.md#amigaos-31--workbench-31)** | Commodore | [`amiga.html`](amiga.html) | Kickstart boot, right-button menus, drag-down screens, the Ram Disk, AmigaShell and the Guru Meditation |
| 1995 | **[Windows 95 (RTM, 4.00.950)](docs/placards.md#windows-95-rtm-400950)** | Microsoft | [`win95.html`](win95.html) | The day the modern desktop was invented: the Start button, teal desktop, two-pane Explorer, the Recycle Bin, Device Manager and the orange it's-now-safe farewell |
| 1995 | **[NeXTSTEP 3.3](docs/placards.md#nextstep-33)** | NeXT | [`nextstep.html`](nextstep.html) | The black slab: Workspace Manager, the Dock's ancestor, and the design language that shaped OS X |
| 1996 | **[Novell NetWare 4.11 (IntranetWare)](docs/placards.md#novell-netware-411-intranetware)** | Novell | [`netware411.html`](netware411.html) · [`netware.html`](netware.html) | One server, two ways in: the full IntranetWare experience with DOS boot, the blue login, SYSCON and FILER, or a console-only session of MONITOR and NDS |
| 1997 | **[Solaris 2.6 / CDE 1.2](docs/placards.md#solaris-26--cde-12)** | Sun Microsystems | [`solaris.html`](solaris.html) | The Unix industry's peace treaty: the one desktop HP, IBM, Sun and Novell built together, with four workspaces that restore every window exactly where you left it |
| 1997 | **[Slackware Linux 3.4.0](docs/placards.md#slackware-linux-340)** | Patrick Volkerding / Walnut Creek CDROM | [`slackware.html`](slackware.html) | You install the operating system, and that is the exhibit: boot floppies, an fdisk with no undo, disk sets with no dependency information, then xf86config |
| 1999 | **[QNX 4.25 — The Incredible 1.44M Demo](docs/placards.md#qnx-425--the-incredible-144m-demo)** | QNX Software Systems | [`qnx.html`](qnx.html) | A proof on one floppy: a hard real-time microkernel, the Photon GUI, TCP/IP, a web server and a graphical browser — slay the GUI and the machine keeps running |
| 2000 | **[BeOS R5](docs/placards.md#beos-r5)** | Be Inc. | [`beos.html`](beos.html) | Tracker, Deskbar and the multimedia OS that was too good to live |
| 2001 | **[Mac OS 9.2.2](docs/placards.md#mac-os-922)** | Apple | [`macos9.html`](macos9.html) | Platinum at its peak — the classic Finder's last stand |
| 2001 | **[Mac OS X 10.0 “Cheetah”](docs/placards.md#mac-os-x-100-cheetah)** | Apple | [`cheetah.html`](cheetah.html) | First-generation Aqua: lickable buttons, the original Dock, Unix underneath |
| 2001 | **[IBM OS/2 Warp 4.52](docs/placards.md#ibm-os2-warp-452)** | IBM | [`os2warp.html`](os2warp.html) | Boot Manager, CONFIG.SYS and the object-oriented Workplace Shell |
| 2002 | **[Plan 9 from Bell Labs, Fourth Edition](docs/placards.md#plan-9-from-bell-labs-fourth-edition)** | Bell Labs | [`plan9.html`](plan9.html) | Unix's authors' second attempt: everything really is a file and every window is its own namespace — `cat /dev/mouse`, `bind`, acme, rc, sam and the plumber all work |
| 2004 | **[Windows XP Service Pack 2](docs/placards.md#windows-xp-service-pack-2)** | Microsoft | [`winxp.html`](winxp.html) | The release where the default flipped from open to closed: turn the firewall off, dial up, and meet the sixty-second shutdown countdown — then turn it back on |
| 2005 | **[Mac OS X 10.4 “Tiger”](docs/placards.md#mac-os-x-104-tiger)** | Apple | [`tiger.html`](tiger.html) | The release that bet the filing cabinet was finished: Spotlight, Smart Folders and mdfind as clients of one metadata index, plus Dashboard, brushed metal and Rosetta |
| 2006 | **[超漢字V (Chokanji V)](docs/placards.md#超漢字v-chokanji-v)** | Personal Media / TRON | [`chokanji.html`](chokanji.html) | The last living BTRON: a filesystem that is a web rather than a tree — 実身 objects and 仮身 references, no directories, no paths — and 180,000 characters |
| 2012 | **[Windows 8 (RTM, build 9200)](docs/placards.md#windows-8-rtm-build-9200)** | Microsoft | [`win8.html`](win8.html) | Two operating systems bolted together, as shipped: live tiles, charms and semantic zoom in front of a desktop with a conspicuously bare bottom-left corner |
| 2017 | **[TempleOS 5.03](docs/placards.md#templeos-503)** | Terry A. Davis | [`templeos.html`](templeos.html) | One man's operating system and public-domain religious artefact: 640×480, sixteen colours, ring 0, a prompt that is the compiler, and files that are living documents |
| 2023 | **[IBM z/OS 3.1](docs/placards.md#ibm-zos-31)** | IBM | [`zos.html`](zos.html) | A 3270 terminal on a living mainframe: IPL, VTAM logon, TSO/ISPF, JCL, JES2, SDSF and REXX — not a memory but a description of next Tuesday |
| 2024 | **[HelenOS 0.14.1 “Aladar”](docs/placards.md#helenos-0141-aladar)** | HelenOS project | [`helenos.html`](helenos.html) | The microkernel argument, finished: nine architectures at the door, two dozen servers assembling a desktop, and a filesystem server you can kill while the clock ticks on |
| 2025 | **[SymbOS 4.0](docs/placards.md#symbos-40)** | Prodatron / SymbiosiS | [`symbos.html`](symbos.html) | A Win9x-grade multitasking desktop on a 4 MHz Z80: pick a CPC, MSX2, Spectrum Next or PCW and run chiptunes, a raycaster and a file copy at once |
| 2026 | **[KolibriOS 0.7.7.0+](docs/placards.md#kolibrios-0770)** | KolibriOS Team | [`kolibrios.html`](kolibrios.html) | An entire operating system in FASM assembly on a 1.44 MB floppy, booting to a desktop in two seconds and compiling twenty lines of source before you finish reading them |

### 📱 Mobile

| Year | Exhibit | Vendor | File | What you get |
|------|---------|--------|------|--------------|
| 1997 | **[Newton OS 2.1 — MessagePad 2000](docs/placards.md#newton-os-21--messagepad-2000)** | Apple | [`newton.html`](newton.html) | The museum's first hand-held: instant on because an OS in ROM never boots, no files anywhere — just soups — and a handwriting recogniser that is honestly a parody |
| 2000 | **[Palm OS 3.5](docs/placards.md#palm-os-35)** | Palm, Inc. | [`palmos.html`](palmos.html) | The machine that won by subtraction: 160 × 160 pixels, four buttons, no filesystem, no boot and no Save command — HotSync, beam, then flatten the battery |
| 2007 | **[iPhone OS 1.0 — original iPhone](docs/placards.md#iphone-os-10--original-iphone)** | Apple | [`iphoneos.html`](iphoneos.html) | The device that deleted the intermediary: touch the thing itself, on a physics engine built first — and no App Store, no copy and paste, no MMS, no notifications |

## ✨ How the exhibits are built

Every simulation in this museum follows the same rules:

- **One file.** All HTML, CSS and JavaScript live in a single `.html` document.
- **Zero dependencies.** No CDNs, no frameworks, no network requests, no assets to load.
- **Offline-first.** Opening the file from disk is the supported way to run it.
- **Simulation, not emulation.** The pages re-create interfaces and behaviour in the browser; they
  don't execute original software or contain any copyrighted binaries. Where an exhibit goes
  deeper — the C64's BASIC interpreter and its chips, TempleOS's HolyC compiler, RISC OS's Wimp
  and BBC BASIC, GEOS's filesystem and font engine, the Newton's and Palm's handwriting
  recognisers — every byte of it is written from scratch to behave like the real thing.

The landing page ([`index.html`](index.html)) follows the same rules. It renders its gallery
from a small data array, so the museum grows without any structural changes, and its themes are
pure CSS on system fonts — no images, no downloads.

## ➕ Adding a new exhibit

New exhibits are always welcome. To add an OS:

1. **Create the simulation** as a single self-contained file, e.g. `riscos.html`, following
   the rules above (one file, no external resources, works from `file://`).
2. **Pick its wing** — `desktop` or `mobile`, using the [decision rule](#which-wing) above.
   Every exhibit must be placed in exactly one wing; there is no third wing and no "both".
3. **Register it in the gallery** — open [`index.html`](index.html) and append one object to the
   `EXHIBITS` array in the `<script>` block:

   ```js
   {
     file:     "riscos.html",
     name:     "RISC OS 3.11",
     vendor:   "Acorn",
     year:     1992,
     category: "desktop",                  // REQUIRED: "desktop" or "mobile"
     glyph:    "!Boot",                    // shown on the card's mini screen
     desc:     "No menu bar anywhere — every menu comes from the middle mouse button. …",
     accent:   "#f0c000",                  // card accent colour
     bg:       "#2a2a3a",                  // mini-screen background
     tags:     "acorn risc os arm archimedes"  // extra search keywords
   },
   ```

   Search, sorting and the wings pick it up automatically — no other changes needed. Notes on
   the fields:

   - **`desc` is the card's blurb.** Every card is the same height and shows the first **five
     lines** of it — roughly the first 180 characters at desktop width — before a **more…**
     link opens the rest in place. So lead with the sentence that sells the exhibit; the detail
     can follow it. There is no length limit.
   - **`name`** gets two lines on the card; anything longer is cut with an ellipsis.
   - **`accent`** and **`bg`** colour the card in every theme. Pick an accent that reads on the
     dark mini-screen; the page darkens it automatically on light surfaces.
   - **`category`** missing or unrecognised hangs the exhibit in a red **Uncategorised** bin at
     the bottom of the page (and logs a console error), so forgetting it is loud rather than quiet.
   - **`variants`** (optional) — if one exhibit ships several builds, add
     `variants: [{file, label}, …]`; the card shows one launch link per build on a single line
     (see NetWare).

4. **Add a row to that wing's table** in this README: year, name, vendor, file, and **one
   sentence**. Link the name to its placard as `[Name](docs/placards.md#anchor)`, where the anchor
   is GitHub's for the placard heading — the name in lower case, punctuation dropped, spaces as
   hyphens (so `Mac OS X 10.4 “Tiger”` becomes `#mac-os-x-104-tiger`).
5. **Write the placard** in [`docs/placards.md`](docs/placards.md): a `###` heading with the same
   name under the wing's section, in year order; a *vendor · year · file* line; then the long-form
   notes — what the simulation reproduces, why the system mattered, what to try first. That is
   where the essay belongs. The README stays a one-line-per-exhibit index.

### Adding a theme skin to the launcher

The launcher's **Themed** option picks, at random, one of the skins listed in `OSM.SKINS` — the
short bootstrap script in the `<head>` of [`index.html`](index.html). A skin is one CSS block,
`:root[data-skin="…"] { … }`, that overrides the tokens declared on `:root` (colours, fonts,
corner radii, the bevel recipe, the page background) plus, optionally, a few rules under the
*skin details* comment that draw the window chrome every card carries — title bar and buttons — in
that OS's style. To add one:

1. Copy an existing skin block in the stylesheet, rename it and set its tokens; add chrome rules
   if the OS had a distinctive title bar.
2. Add `{ id: "…", name: "…" }` to `OSM.SKINS`; the `id` must match the `data-skin` value, and
   the `name` is what the page shows in "now dressed as …".
3. Keep it self-contained: system font stacks with fallbacks, CSS gradients instead of images,
   nothing downloaded.

## 📄 Notes

- These simulations are fan-made tributes for educational and nostalgic purposes.
  All product names, logos and trademarks belong to their respective owners.
- Best experienced on a desktop browser — most of these interfaces predate touchscreens
  by a decade or more.
