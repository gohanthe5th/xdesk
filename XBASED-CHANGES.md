# XDesk changes to xbased

XDesk 2.x is based on xbased 1.2.12 at commit `577f3b8841e166177c613356050f94980622d579`. Earlier XDesk 2.x releases used xbased 1.0.90 through 1.0.104. This list describes XDesk-specific additions and the changes retained in the Windows build.

## XDesk additions

| Area | Change |
| --- | --- |
| Branding | XDesk executable name, icon, window titles, About screen, Windows file details, and dashboard identity. |
| Home screen | Preserved XDesk's custom dashboard, pixel-art logo, and bundled Xbox background. |
| Wallpaper and clock | Added a background picker and reset option, clock visibility, and 12/24-hour time. |
| Triggers | Independent Analog, Short Pull, or Digital software response for the left and right triggers, with global defaults and per-game overrides. |
| DualSense | Adaptive trigger toggle and independent Off, Resistance, Trigger, or Automatic effects, with per-game overrides and separate diagnostics controls. |
| Covers | Added search by title, region, and edition, artwork preview, **Use this cover**, and persistent manual selections. Downloaded and custom covers are saved in their own folders. |
| Custom soundtracks | Added WMA and MP3 import, duration display, and track removal. MP3 conversion uses the `ffmpeg.exe` included in the Windows package. |
| 3D game cases | Added generated cases and support for custom PNG case art, adapted from xbased PR #268. |
| Updates | Rebranded the startup and manual update checker to use XDesk's GitHub releases and XDesk package names. |
| Networking | Removed Insignia-specific screens, prompts, and setup flow while retaining the emulator's general networking options. |
| Multi-generation library | Added persistent Xbox 360 and Series X|S entries with separate Xenia and XCL launch routes; the built-in original Xbox core remains the default for XBE games. |
| Settings and logs | Uses `xdesk.ini` and `xdesk.log`; if `xdesk.ini` is absent, an existing portable `xbased.ini` can be migrated. |

## Emulator changes retained from xbased 1.2.12

- New 1×, 2×, and 4× downsampling choices for high internal resolutions.
- Graphics corrections including Fable: The Lost Chapters texture handling, Max Payne screen width, and language-folder detection.
- More accurate frame pacing and frame-rate limits under heavy GPU load and in games that present outside the usual interrupt handler.
- Save states can move between `.chd` and `.iso` images of the same dump, and state-load refusals are reported in the log.
- Faster threaded screenshot and save-state work, more controller shortcuts, and updated audio processing and surround mixing.
- Newer input mapping, per-game settings, game-folder detection, and patches and mod support.

The emulator is derived from xbased by crazyriddler, which in turn is based on hakuX. License and third-party notices are retained in the source and release packages.

