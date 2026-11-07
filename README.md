# XDesk

XDesk is an independent Windows app for original Xbox emulation. It combines the [xemu](https://github.com/xemu-project/xemu) emulator with a console dashboard adapted from [xbased](https://github.com/crazyriddler/xbased).

[Download XDesk 1.0.3 for Windows x64](https://github.com/gohanthe5th/xdesk/releases/tag/v1.0.3)

## Getting started

1. Extract the Windows ZIP and run `XDesk.exe`.
2. Open **Settings → System / BIOS / storage** to configure your Xbox firmware and virtual hard disk. Supply your own firmware and game images.
3. Open **Games** to add your game images. Press **F1** to return to the dashboard or **F2** to open the quick menu.

## Game covers

XDesk saves downloaded covers in `covers` inside its settings folder. If a game has no artwork, open its details and select **Choose cover image** below **Play**. XDesk copies the image into `covers/custom`, so the original can be moved afterward.

Version 1.0.3 also includes the redesigned game grid and game details, the built-in cartoon Xbox background, and the DualSense trigger and diagnostic controls.

## Source and licenses

The release includes `XDesk-source.zip` with the corresponding source and build instructions. See [LICENSE.txt](LICENSE.txt) for copyright notices and license texts. Cover downloads use the [Libretro Xbox cover catalog](https://github.com/libretro-thumbnails/Microsoft_-_Xbox).
