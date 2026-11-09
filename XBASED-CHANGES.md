# XDesk changes to xbased 1.0.90

The XDesk 2.x line starts from xbased 1.0.90 at commit `d3abca5c2996744d167b20dc419947041272533c`. The list below covers changes in the Windows fork through v2.0.2.

## Changes made in XDesk

| Area | Change |
| --- | --- |
| Branding | XDesk executable, icon, window titles, About screen, Windows file details, and dialog text. |
| Home screen | Pixel-art XDesk logo replaces the orb and wordmark. |
| Wallpaper | Bundled cartoon Xbox artwork, a PNG/JPEG picker, a toggle, and a reset to the bundled wallpaper. |
| Clock | Added a clock and date visibility toggle and displayed the clock on Home. The 12/24-hour setting comes from upstream. |
| Trigger response | Independent Analog, Short Pull, or Digital response for each trigger, with global defaults and per-game overrides. |
| DualSense | Added an adaptive-trigger toggle and independent Off, Resistance, Trigger, or Automatic motor effects, with per-game overrides. |
| Covers | Added title, region, and edition search, artwork preview, and **Use this cover**. Manual selections survive automatic downloads. Also corrected catalog parsing to accept whitespace in GitHub's JSON. |
| Settings and logs | Uses `xdesk.ini` and `xdesk.log`. If the new settings file is absent, XDesk migrates an existing `xbased.ini` in the portable folder. |
| Distribution | Disabled xbased's automatic updater. XDesk releases ship as a portable ZIP with corresponding source and SHA-256 checksums. |

## Inherited from xbased

The emulator and dashboard, game library and automatic cover matching, Xbox save import, per-game patches and trainers, widescreen database, frame-rate options, and core graphics and audio features come from xbased. The previous xemu-based XDesk releases are documented separately in [the changelog](CHANGELOG.md).
