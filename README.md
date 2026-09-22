# Claymore Law Mount Wheel

A mount radial wheel for Guild Wars 2, as a [Nexus](https://raidcore.gg/Nexus) addon.

## Usage

1. Hold **X**: the mount wheel opens.
2. Point at the mount you want.
3. Release the key: the mount is summoned.

- Release in the center (or tap X quickly) to get the first mount of your order. You can change the center to "last used mount" or "cancel" in the options.
- Picking the mount you are riding dismounts. Picking another mount while mounted swaps to it.
- On WvW maps the key summons Warclaw directly (can be turned off).
- Optional: summon by hovering a slice, without releasing the key.

## Requirements

- [Nexus](https://raidcore.gg/Nexus)
- In the game, every mount needs a key under **Options > Control Options > Mount**.
- Set the same keys once in the addon's options (see below). No addon can read the game's key bindings. Mounts without a key show up red on the wheel. (Keys entered in Nexus > Game Binds are used as a fallback.)

## Installation

Download `claymore-mount-wheel.dll` from the [latest release](../../releases/latest) and put it in the game's `addons/` folder (or install it from Nexus). Updates arrive automatically through Nexus.

## Options

Nexus menu (CTRL+O) > Addons > Claymore Law Mount Wheel:

- **Language:** English (default) or Turkish
- What a center release / quick tap does: first mount, last used mount, or cancel
- Open the wheel at the screen center or at the mouse cursor
- Move the cursor to the center when the wheel opens
- Wheel size, visible mounts and their order
- Fine tuning: tap threshold, remount delay, hover time
- **Game keys:** click the button next to each mount and press the key you gave that mount in the game. Same for Mount/Dismount (used to dismount). CTRL/SHIFT/ALT combinations are supported. ESC cancels.

To change the wheel key itself (X): Nexus > Keybinds.

## Known limitations

- Doesn't work in Action Camera mode.
- Game keys bound to mouse buttons are not supported.
- ESC and keys already used by other Nexus addons can't be assigned.

## Note

This repository only distributes releases (the DLL). Please use [Issues](../../issues) for bug reports.
