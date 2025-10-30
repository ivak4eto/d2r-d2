## 🧩 D2R-D2 — Runewords from Diablo II: Resurrected in Classic Diablo II (1.14d)

![D2R](https://github.com/ivak4eto/d2r-d2/blob/main/IMG_0671.jpeg)


## ⚔️ Overview

D2R-D2 is a lightweight mod that ports most Diablo II: Resurrected (v2.6) runewords into Diablo II: Lord of Destruction (1.14d).
It allows single-player users to enjoy the newer runewords without needing D2R or Battle.net.

This project modifies the game’s .txt data files and uses the built-in -direct -txt launch method.
No executable or binary patches — completely safe and easy to remove.

## 🛠️ Installation

1. Copy the "data" folder to your Diablo II installation directory.

Example:

```shell
C:\Program Files (x86)\Diablo II\data
```

2. Edit your Diablo II shortcut to include the following at the end of the Target line:

```shell
-direct -txt
```

Example full line:

```shell
"C:\Program Files (x86)\Diablo II\Game.exe" -direct -txt
```

3. Launch the game normally — the new runewords will now be available.


## ⚡ Compatibility

D2R 2.6 runewords	✅ Most fully working

Multiplayer / Battle.net	❌ Not supported

Single-player / TCP/IP	✅ Works if all players use same mod

Executable patching	❌ None (data-only mod)


## 💎 Runewords Summary


Mosaic	⚠️	Some effects missing

Metamorphosis	⚠️	Slight stats issues

Hustle	✅	Fully functional

Plague	✅	Fully functional

Flickering Flame	✅	Fully functional

Wisdom	✅	Works fine

Obsession	✅	Fully functional

Pattern	✅	Fully functional

Temper	✅	Fully functional

Cure	✅	Fully functional

Unbending Will	✅	Fully functional

Bulwark	✅	Fully functional

Ground	✅	Fully functional

Hearth	✅	Fully functional

Temper	✅	Fully functional

Hustle	✅	Fully functional

Mist	✅	Works fine

Obedience / Pride / Insight / etc.	✅	All original LoD runewords untouched


## ⚙️ How It Works

The mod includes updated files (Runes.txt & patchstring.tbl). By launching Diablo II with the -direct -txt flags, the game loads that data file directly instead of those packed inside the MPQ archives.

No game binaries are altered — the mod is safe, reversible, and EULA-friendly for offline play.


## ⚠️ Known Issues

Some newer D2R stats are not recognized by LoD.

This mod is not intended for online environments (Battle.net) — single-player only.


## 💬 Credits

Author: [ivak4eto](https://github.com/ivak4eto/)

Game: Diablo II: Lord of Destruction (1.14d)

Reference: Diablo II: Resurrected v2.6 (for runeword definitions)

## ❤️ Enjoy!
