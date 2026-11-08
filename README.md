# XDesk

XDesk is an independent Windows app for original Xbox emulation. It combines the [xemu](https://github.com/xemu-project/xemu) emulator with a console dashboard adapted from [xbased](https://github.com/crazyriddler/xbased).

[Download XDesk 1.0.12 for Windows x64](https://github.com/gohanthe5th/xdesk/releases/tag/v1.0.12)

## Getting started

1. Extract the Windows ZIP and run `XDesk.exe`.
2. Open **Settings → System / BIOS / storage** to configure your Xbox firmware and virtual hard disk. Supply your own firmware and game images.
3. Open **Games** to add your game images. Press **F1** to return to the dashboard or **F2** to open the quick menu.

## Game covers

XDesk matches cover art using the disc title, region, and filename. XDesk saves downloaded covers in `covers` inside its settings folder. If a game has no artwork, open its details and select **Choose cover image** below **Play**. XDesk copies the image into `covers/custom`, so the original can be moved afterward.

XDesk includes the redesigned game grid and game details, the built-in cartoon Xbox background, and the DualSense trigger and diagnostic controls.

## Display settings

- Under **Settings → Display**, select **Vulkan** to choose a graphics card or leave it on **Automatic**. Restart XDesk to apply the choice. With OpenGL, use the Windows graphics settings shortcut.
- Under **Settings → Display → Interface**, turn the dashboard clock on or off and choose 12-hour (AM/PM) or 24-hour time.

## Library and backup

- Add games to **Favorites** or named collections from the game details screen. **Continue playing** opens the last game you launched from the library.
- Use **Search covers** in game details to preview and apply another edition’s cover.
- Use **Settings → General → Backup and restore** to save your library, artwork stored in XDesk, controller settings, and display preferences. Restart XDesk to apply a queued restore. Keep your game images separately.
- The first-run wizard guides you through firmware, virtual storage, and the games folder. Reopen it from **Settings → General → Open setup wizard**.

## Updates

Open **Settings → About XDesk → Check for updates** to check the latest stable GitHub release. If a newer build is available, **Download Windows update** opens the ZIP in your browser. Close XDesk before replacing the executable.

See [CHANGELOG.md](CHANGELOG.md) for release history.

## Source and licenses

The release includes `XDesk-source.zip` with the corresponding source and build instructions. See [LICENSE.txt](LICENSE.txt) for copyright notices and license texts. Cover downloads use the [Libretro Xbox cover catalog](https://github.com/libretro-thumbnails/Microsoft_-_Xbox).
