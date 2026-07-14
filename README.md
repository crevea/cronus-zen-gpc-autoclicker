# Crev Auto — RT Auto Clicker

A GPC script for the Cronus Zen that turns your Xbox controller's **RT** trigger into a toggleable auto-clicker. Tap once to turn it on, tap again to turn it off — no need to hold the trigger down.

## Features

- **Toggle on/off** with a single RT tap, running at ~333 clicks/sec
- **Animated OLED menu** with a real-time loading bar on boot
- **Snow effect** drifting across the whole screen
- **Pulsing border** that shows when the clicker is actively running
- **Vibration feedback** on every toggle
- Lightweight and easy to tweak — all key values are `define`d at the top of the script

## Requirements

- [Cronus Zen](https://cronusmax.com/)
- Cronus Zen Studio (to compile and upload the script)
- Xbox controller

## Installation

1. Download `crev_auto_r2_clicker.gpc` from this repo
2. Open Cronus Zen Studio
3. Load the script into an empty slot
4. Compile and save it to your Zen device

## Usage

| Action | Result |
|---|---|
| Tap RT | Toggle auto-clicker ON/OFF |

The OLED shows a boot animation on power-up, then the live status.

## Configuration

All key settings live near the top of the script:

| Variable | Description | Default |
|---|---|---|
| `PRESS_DELAY` / `RELEASE_DELAY` | Click speed (ms) | `1` / `2` (~333 CPS) |
| `BOOT_DURATION` | Boot animation length (ms) | `900` |
| `SNOW_COUNT` | Number of snowflakes | `12` |

## Disclaimer

This script is intended for personal testing and non-competitive use. Auto-clickers and macro devices violate the Terms of Service of most games, including Roblox. Use at your own risk.

## License

MIT
