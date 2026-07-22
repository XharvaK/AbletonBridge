# Ableton workspace

Live 12 Suite + AbletonBridge MCP for Cursor agent control.

Fork: [XharvaK/AbletonBridge](https://github.com/XharvaK/AbletonBridge) · upstream [hidingwill/AbletonBridge](https://github.com/hidingwill/AbletonBridge)

## Paths

| What | Path |
|------|------|
| Project | `C:\Users\Xharv\Projects\Ableton` |
| Live exe | `E:\Ableton 12\Program\Ableton Live 12 Suite.exe` |
| Remote Script | `Documents\Ableton\User Library\Remote Scripts\AbletonBridge` |

## First-run in Live (Doc)

1. Launch **Ableton Live 12 Suite**.
2. Preferences → **Link, Tempo & MIDI**.
3. Control Surface: **AbletonBridge**
4. Input / Output: **None**
5. Restart Cursor so MCP picks up AbletonBridge.
6. In Agent chat: *Get information about my Ableton session*

Dashboard (optional): http://127.0.0.1:9880

## Git

- `origin` → your fork (`XharvaK/AbletonBridge`)
- `upstream` → `hidingwill/AbletonBridge` (pull updates with `git fetch upstream && git merge upstream/main`)

## Agent notes

- Prefer compound workflow tools over tiny one-off calls.
- Save the Live set before large agent runs.
- Only one MCP host at a time (Cursor **or** Claude Desktop).
