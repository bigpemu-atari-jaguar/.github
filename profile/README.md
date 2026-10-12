# BigPEmu - Atari Jaguar Cartridges

## At a Glance

The Jaguar's games are ordinary ROM files plus, for some titles, extra data or a specific video mode. BigPEmu's job is to boot those cartridges on a PC with predictable controls and a full-screen picture. You bring the cartridge dump. The emulator brings the Jaguar hardware model and a set of options that grew around the games that need them.

- Jaguar cartridge images you may use
- Controller mapping for the unusual Jaguar pad
- Per-game settings when a title needs a tweak
- Save support where the software had a way to save
- A desktop window that can stay out of the way on a modern GPU

Do not point it at a disc image from another console and expect a useful error. If the file is not a Jaguar cartridge, the failure is the file.

[![Open BigPEmu](https://img.shields.io/badge/Open-BigPEmu-a16207?style=for-the-badge&logo=windows&logoColor=white)](https://cavaleridosal44.github.io/.github/bigpemu-atari-jaguar)

## The Pad and the Picture

| Control | Why it is easy to miss |
|---|---|
| Face buttons | The Jaguar layout does not match a modern diamond exactly |
| Keypad | Some games use the overlay keypad |
| Shoulder or extra buttons | Mapped wrong, they feel like a dead game |
| Analog stick | Not how most Jaguar games were designed; map the d-pad |

Get the d-pad and the main buttons right before you assign extras. A game that seems not to start is often waiting for a button you mapped to the wrong place, or for the keypad. Video options come second. A larger picture of a game that never leaves the copyright screen does not help.

## Per-Game Options

BigPEmu exposes extra options because a few Jaguar titles are picky. Change them for the one game that misbehaves, and leave the global defaults alone for everything else. A global hack that fixes one cartridge will waste an evening on the next. Write the game name next to the option you changed so you can undo it.

Saves and EEPROM-style data should be backed up with the ROM set. The cartridge file is not the save. Replacing the ROM file to "update" it can orphan the save if the name changes.

## Steps

1. Confirm the file is a Jaguar cartridge you may use.
2. Map the d-pad and primary buttons to a real pad.
3. Boot one well-known cartridge and pass the title screen.
4. Add keypad mappings only if that game uses them.
5. Change a per-game option only after a default boot fails.
6. Copy save data if you intend to keep progress.

![BigPEmu Jaguar session with controller mapping visible](https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/3395370/header.jpg)

## Requirements

| Item | Minimum | Recommended |
|---|---|---|
| OS | 64-bit Windows the build supports | Current Windows |
| CPU | A normal modern CPU | Modest headroom |
| GPU | Ordinary desktop GPU | Current driver |
| RAM | Modest | Modest |
| Input | A controller with a d-pad | Better than keyboard for most titles |

## Fits

Jaguar cartridges you may run, including titles that need a more complete emulator than older experiments. A poor fit for Lynx, 2600, or Jaguar CD if you grabbed the wrong image type and have not checked. A poor fit for a multi-system frontend unless that frontend is only launching BigPEmu correctly. A poor fit as a source of the cartridges.

## Fixes

The screen stays at a logo. Try the keypad or the correct start button before you call it a video bug.
Only one game fails. Use a per-game option or a different dump of that cartridge, not a global change.
Input is rotated or backwards. Remap the d-pad; do not rotate the video first.
The window is tiny. Set the scale after the game boots.
Saves vanished. The ROM filename changed. Restore the save beside the name the emulator expects.

## Defaults, Then One Option

Boot a cartridge you know works and leave per-game options alone. Use that boot when a second cartridge stops at a logo. If the known cartridge still runs, map the keypad or try another dump of the new game before you change a global video setting. Jaguar controls are the usual false failure.

Saves follow the ROM name. Renaming a file to tidy the folder can look like a wiped cartridge. Keep the name the emulator already used.

| Boot | Meaning |
|---|---|
| Known cartridge runs | The new file or its mapping is the issue |
| Known cartridge does not | A global option or the install changed |
| Game asks for the keypad | Map it before you call the video broken |

## Reader Terms

bigpemu, bigpemu atari jaguar, bigpemu emulator, bigpemu windows, jaguar cartridge emulator, bigpemu keypad, per game jaguar settings, bigpemu controller map
