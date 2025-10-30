## 🧩 D2R-D2 — Runewords from Diablo II: Resurrected in Classic Diablo II (1.14d)
⚔️ Overview

D2R-D2 is a lightweight mod that ports most Diablo II: Resurrected (v2.6) runewords into Diablo II: Lord of Destruction (1.14d).
It allows single-player users to enjoy the newer runewords without needing D2R or Battle.net.

This project modifies the game’s .txt data files and uses the built-in -direct -txt launch method.
No executable or binary patches — completely safe and easy to remove.

## 🛠️ Installation

Download the latest version or clone the repo.

Copy the data folder to your Diablo II installation directory.
Example:

C:\Program Files (x86)\Diablo II\data


Edit your Diablo II shortcut to include the following at the end of the Target line:

-direct -txt


Example full line:

"C:\Program Files (x86)\Diablo II\Game.exe" -direct -txt


Launch the game normally — the new runewords will now be available.

## ⚡ Compatibility
Feature	Status
Diablo II version	1.14d (LoD)
D2R 2.6 runewords	✅ Most work
Multiplayer / Battle.net	❌ Not supported
Single-player / TCP/IP	✅ Works if all players use same mod
Executable patching	❌ None (data-only mod)
💎 Runeword Compatibility Summary
Runeword	Works	Notes
Mosaic	✅	Fully functional

Metamorphosis	✅	Slight visual stat issues

Hustle	✅	Works as intended

Plague	⚠️	Works, but aura effect may differ slightly

Flickering Flame	✅	Works fully

Wisdom	✅	Fully functional

Obsession	⚠️	Most stats work, some visual glitches

Pattern	✅	Functional on claws

Temper	✅	Works fine

Cure	⚠️	Works, but aura visuals may be inconsistent

Unbending Will	✅	Fully functional

Bulwark	✅	Works fine
Ground	✅	Works fine
Hearth	✅	Works fine
Temper	✅	Works fine

Devotion	⚠️	Minor inconsistencies

Mist	⚠️	Some effects missing

Obedience / Pride / Insight / etc.	✅	All original LoD runewords untouched

## ⚙️ How It Works

The mod includes updated .txt files (Runewords.txt, Runes.txt, ItemStatCost.txt, and others) extracted from D2R and adapted for compatibility with LoD’s 1.14d engine.
By launching Diablo II with the -direct -txt flags, the game loads these data files directly instead of those packed inside the MPQ archives.

No game binaries are altered — the mod is safe, reversible, and EULA-friendly for offline play.

##⚠️ Known Issues

Some newer D2R stats are not recognized by LoD (they show blank or have no effect).

Certain visual or tooltip bugs may appear, but items function correctly.

Using this mod in online environments (Battle.net) will desync or cause version mismatch errors — single-player only.

## 💬 Credits

Author: ivak4eto

Game: Diablo II: Lord of Destruction (1.14d)

Reference: Diablo II: Resurrected v2.6 data (for runeword definitions)

## ❤️ Support

If you enjoy this mod, star the repository and share feedback or compatibility reports.
Pull requests for improved compatibility or new features are welcome.
