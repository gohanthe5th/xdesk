# XDesk

![Pixel-art XDesk logo](https://github.com/gohanthe5th/xdesk/releases/download/v2.0.1/XDesk-v2.0.1-Menu-Art.png)

XDesk is a portable original Xbox emulator for Windows x64, based on [xbased 1.2.12](https://github.com/crazyriddler/xbased/releases/tag/v1.2.12). It keeps XDesk's console-style dashboard and custom controller, artwork, and soundtrack features.

[Download XDesk v2.1.0](https://github.com/gohanthe5th/xdesk/releases/tag/v2.1.0)

## Getting started

1. Extract the full Windows ZIP into a new folder and run `XDesk.exe`.
2. Open **Games** to add ISO, XISO, or extracted game folders.
3. Choose a game to play or open its settings, controls, and **Mods & patches**.

The portable build keeps settings, saves, snapshots, covers, and other data beside the executable. When startup updates are enabled, XDesk checks GitHub for a newer stable release and offers its installer.

## Features

- Per-game patches, cheats, widescreen options, and frame-rate settings.
- Internal resolution up to 8×, video modes, aspect ratio, FXAA, anisotropic filtering, bilinear or FSR upscaling, and CRT looks. Settings can be global or per game.
- **Downsampling** at 1×, 2×, or 4× for smoother edges while retaining the original look.
- DualSense input, independent left and right trigger response, and adaptive-trigger effects with per-game overrides.
- Automatic cover downloads plus **Search covers** and preview to correct a mismatched edition.
- Custom soundtrack management. Add WMA or MP3 tracks, view durations, and remove tracks; MP3 conversion uses the included `ffmpeg.exe`.
- Automatic updates from XDesk's GitHub releases, with a setting to turn startup checks off or on.

## Custom soundtracks

Open **Memory → Manage soundtrack music** to add or remove tracks. In games that support custom soundtracks, choose **XDesk Music** from the game's soundtrack menu.

## Settings and saves

- **Interface** includes the dashboard background, clock, and 12/24-hour format.
- **Controls → Triggers** configures left and right trigger response and DualSense adaptive effects, globally or for a game.
- **Settings → Interface → 3D game cases** switches between 3D and flat covers. Custom case artwork can be placed at `covers/<game-key>-3d.png`.
- Compatible in-game saves can be imported from a legacy XDesk/xemu TOML and HDD image. Save states and settings are specific to this build.

See [the full change history](CHANGELOG.md) and [XDesk's additions to xbased](XBASED-CHANGES.md).

## Source and license

The release includes the corresponding source, pinned dependencies, build instructions, and third-party notices. XDesk is distributed under GPL-3.0-or-later. See [LICENSE.txt](LICENSE.txt), [COPYING](COPYING), and the notices in `licenses/`.

