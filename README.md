# Control Resonant Save Editor

A save file editor for **Control Resonant** (Remedy Entertainment, 2026) — edit progress, inventory, and other save data on PC.

![platform](https://img.shields.io/badge/platform-Windows-blue)
![status](https://img.shields.io/badge/status-early%20access-orange)
![license](https://img.shields.io/badge/license-MIT-green)

## Features

- Edit character progress (level, abilities, health/energy caps)
- Edit inventory and resources
- Safe editing with automatic backup of the original save before any write
- Works with Steam and Epic Games save locations

## Download

Grab the latest release from the [Releases](../../releases) page:

**`ControlResonant-SaveEditor-v1.0.0.zip`**

Unzip and run `ControlResonantSaveEditor.exe`. No installation required.

## Save File Location

| Platform | Path |
|---|---|
| Steam | `C:\Program Files (x86)\Steam\userdata\[YourSteamID]\[AppID]\remote` |
| Epic Games | `%LOCALAPPDATA%\Remedy\ControlResonant\Saves` |

The tool can auto-detect these locations or let you point to a save file manually.

## Usage

1. Close Control Resonant before editing your save.
2. Launch `ControlResonantSaveEditor.exe`.
3. Select your save file (or let the tool auto-detect it).
4. Make your edits.
5. Save — a backup of your original file is created automatically in the same folder.

## ⚠️ Disclaimer

This is an unofficial, fan-made tool with no affiliation to Remedy Entertainment. Editing save files is done at your own risk. Always keep a backup. May break with future game updates as the save format changes.

## Contributing

Issues and pull requests are welcome — especially help mapping additional save fields as the format is reverse-engineered further.

## License

MIT
